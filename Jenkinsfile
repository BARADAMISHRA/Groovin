pipeline{
    agent any
    stages{
        stage{
          steps{
            script {
              def disk_size = sh(script: "ssh remote-server df / --output=avail | tail -1", returnStdout: true).trim() as Integer
               println("disk_size = ${disk_size}")
            }
          }
        }
    }
}
