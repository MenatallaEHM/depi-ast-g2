pipeline {
agent any

stages{

     stage("bulid")
       {
           steps{
            sh """
                  npm -v
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
