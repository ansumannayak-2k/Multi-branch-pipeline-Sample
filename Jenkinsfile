pipeline{
  agent any
  stages{
    stage{'Build'} {
      step{
        echo "Building Branch : ${env.main}"
      }
    }
    stage{'Test'} {
      step{
        echo "Testing branch : ${env.main}"
      }
    }
    stage{'Deploy'} {
      step{
        echo "Delpoying Branch : ${env.main}"
      }
    }
  }
}
