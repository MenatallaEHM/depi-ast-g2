pipeline {
agent any

//tools{
//   nodejs 'node25'
//}
stages{

     stage("bulid docker")
       {
           steps{
            sh """
                  docker build -t docker.io/MenatallaEHM/myapp:vi
              """
            }
        }
       stage("test")
       {
           steps{
            sh """
                  echo "test code"
              """
            }
        }
       stage("build docker")
       {
           steps{
            sh """
                  echo "build docker image"
              """
            }
        }
       stage("deploy")
       {
           steps{
            sh """
                  echo "ssh to target server"
              """
            }
        }
}
}
