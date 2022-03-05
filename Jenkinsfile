pipeline{
    agent{
        label "node"
    }
    stages{
        stage("compiling"){
            steps{
                step{
                    echo " this is 1st time compiling"
                }
               
            }
        }
        stage("Building"){
            steps{
                step{
                    echo "this is 1st building phase"
                }
               
            }
        }
        stage("Testing"){
            steps{
                step{
                    echo " this is my 1st testing phase"
                }
               
            }
        }
        stage("deploying"){
            steps{
                step{
                    echo "this is 1st stage of deploying"
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
