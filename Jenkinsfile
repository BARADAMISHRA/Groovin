pipeline{
    agent{
        label "node"
    }
    stages{
        stage("getting"){
            steps{
                echo "========executing A========  ${BUILD_NUMBER}"
                echo "Jenkins URL ${JENKINS_URL}"
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
