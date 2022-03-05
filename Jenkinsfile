pipeline{
   agent any 
   stages{
       stage("build"){
          steps{
             sh "echo hello world"
             sh "hostname"
             sh  "uptime"
             
            }
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
