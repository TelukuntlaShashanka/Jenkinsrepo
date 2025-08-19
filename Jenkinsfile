pipeline{
  agent any
    stages{
      stage('Build'){
        steps{
          echo 'No build step for now'
          //git'https://github.com/TelukuntlaShashanka/Jenkinsrepo.git'
        }
      }
stage('Test'){
  steps{
      //echo "checking existence.."
     // sh 'ls -1 index.html'
    sh 'npm test'
    }
  }
  stage('Deploy'){
    when {
      branch 'main'
    }
    steps{
      echo "Deploying (simulated)"
}
}
}
}
