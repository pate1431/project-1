pipeline{
  agent any
  stages{
    stage("build"){
      steps{
        sh "echo Jay Shree Ram using Jenkins File"
        sh "echo Jay siya ram"
      }
    }
    stage("installation"){
      steps{
        sh "sudo apt-get install docker-engine -y"
        sh " sudo service docker start"
        sh " sudo docker run hello-world"
      }
    }
  }
}
