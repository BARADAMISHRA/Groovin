pipeline{
    agent any
    environment{
        Example_variable  = "1"
    }
    stages{
        stage("enviornment"){
            steps{
                echo "Build number is  ${BUILD_NUMBER}"
                echo "Build number is ${env.BUILD_NUMBER}"
            }
        }
    }
     
}
