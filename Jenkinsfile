pipeline{
  agent any
    stages{
      stage('checkout'){
        steps{
          git'https://github.com/TelukuntlaShashanka/Jenkinsrepo.git'
        }
      }
stage('Validate'){
  steps{
      echo "checking existence.."
      sh 'ls -1 index.html'
    }
  }
  stage('Deploy'){
    steps{
      echo "Deploying (simulated)"
}
}
}
}
