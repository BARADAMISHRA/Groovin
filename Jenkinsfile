pipeline{
    agent any
    stages{
        stage("compile"){
            steps{
                step{
                    echo "Compiling A========"
                }
                
                
            }
            
       }
        stage("Building"){
            steps{
                step{
                    echo "Building a code"
                }
               
                
            }
        }
        stage("Testing"){
            steps{
                step{
                  echo "Testing a code"
                }
                
               
            }
        }
        stage("Deploying"){
            steps{
                step{
                   echo "Deploying a code"
                }
              
            }
        }

    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}
