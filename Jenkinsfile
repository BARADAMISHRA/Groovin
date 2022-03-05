pipeline{
    agent any
    stages{
        stage("compile"){
            steps{
                    echo "Compiling A========"
                }
                
                
            }
            
       }
        stage("Building"){
            steps{
                    echo "Building a code"
                }
               
                
            }
        }
        stage("Testing"){
            steps{
                  echo "Testing a code"
                }
                
               
            }
        
        stage("Deploying"){
            steps{
                
                   echo "Deploying a code"
                
              
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
