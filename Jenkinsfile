pipeline{
    agent any
    stages{
        stage{
          steps{
              script{
                  def disk_size=sh(script: "hostname")
                  println("disk size is ${disk_size}")
              }
          }
        }
    }
}
