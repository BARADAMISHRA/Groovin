pipeline{
    agent any
    environment{
       app= "java"
       tech= "cloud"
    }
    stages{
        stage("enviornment"){
            steps{
                echo "Build number is  ${BUILD_NUMBER}"
                echo "Build number is ${env.BUILD_NUMBER}"
                echo "app name is ${env.app}"
                echo "tech is ${env.tech}"
            }
        }
    }
     
}
