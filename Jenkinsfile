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
                step{
                    echo " this is 2nd time compiling"
                }
            }
        }
        stage("Building"){
            steps{
                step{
                    echo "this is 1st building phase"
                }
                step{
                    echo "this is 2nd building phase"
                }
            }
        }
        stage("Testing"){
            steps{
                step{
                    echo " this is my 1st testing phase"
                }
                step{
                    echo "this is my 2nd testing phase"
                }
            }
        }
        stage("deploying"){
            steps{
                step{
                    echo "this is 1st stage of deploying"
                }
                step{
                    echo "this is 2nd stage of deploying"
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
