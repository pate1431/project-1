pipeline{
  agent any
  stages{
    stage("build"){
      steps{
        sh 'git checkout snehal'
        sh "echo Jay Shree Ram dasjdaksjbdjasbdasbjkbasc> box.txt" 
      }
    }
    stage("installation"){
      steps{
        sh "git add ."
        sh 'git commit -m "snehal"'
        sh "git push -u origin snehal"
      }
    }
  }
}
