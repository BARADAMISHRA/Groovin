pipeline{
    agent any
    stages{
        stage("compile"){
            steps{
                step{
                    echo "Compiling A========"
                }
                step{
                    echo "Compiling B========"
                }
                
            }
            
       }
        stage("Building"){
            steps{
                step{
                    echo "Building a code"
                }
                step{
                    echo "Building b code"
                }
                
            }
        }
        stage("Testing"){
            steps{
                step{
                  echo "Testing a code"
                }
                step{
                     echo "Testing b code"
                }
               
            }
        }
        stage("Deploying"){
            steps{
                step{
                   echo "Deploying a code"
                }
               step{
                    echo "Deploying b code"
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
