pipeline{
    agent any
    stages{
        stage("getting"){
            steps{
                echo "========executing A========  ${BUILD_NUMBER}"
                echo "Jenkins URL ${JENKINS_URL}"
            }
            
        }
        parameters {
          string(name: 'environment', defaultValue: 'DEV', description: 'Deployment environment?')
          booleanParam(defaultValue: true, description: 'Skip Tests?', name: 'skiptest')
          text(defaultValue: "Multiple lines text \n another line", description: "Multi-line", name: "multiline")
          choice(choices: 'AWS,AZURE,GCP', description: 'Which cloud platform?', name: 'cloudplatform')
          password(defaultValue: "Password", description: "enter test account password", name: "testpwd")
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
