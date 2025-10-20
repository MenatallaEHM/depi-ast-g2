pipeline {
agent any

stages{

     stage("bulid")
       {
           steps{
            sh """
                  echo "Buils node code"
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
       stage("build docker")
       {
           steps{
            sh """
                  echo "ssh to target server"
              """
            }
        }
}
}
