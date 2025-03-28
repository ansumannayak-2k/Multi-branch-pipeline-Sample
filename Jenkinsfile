pipeline{
  agent any
  stages{
    stage('Build') {
      steps{
        echo "Building Branch : ${env.main}"
      }
    }
    stage('Test') {
      steps{
        echo "Testing branch : ${env.main}"
      }
    }
    stage('Deploy') {
      steps{
        echo "Delpoying Branch : ${env.main}"
      }
    }
  }
}
