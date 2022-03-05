pipeline{
   agent any 
   stages{
    steps{
           sh "echo hello world"
           sh "hostname"
           sh  "uptime"
           sh "downtime"
    }
   }
   post{
       always{
           echo "success always block executing"
       }
       success{
           echo  "success block is executing"
       }
       failure{
           echo "Failure block is executing"
       }
   }
}
