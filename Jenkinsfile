pipeline{
  agent any
  stages{
    stage("build"){
      steps{
        sh 'git branch snehal'
        sh 'git checkout snehal'
        sh "echo Jay Shree Ram using Jenkins File > simple.txt" 
        sh "echo Jay siya ram >> simple.txt"
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
