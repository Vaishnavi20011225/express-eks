pipeline{
  agent any
  triggers{
    pollSCM '*/5 * * * *'
  }
  stages {
    stage ('Build'){
      steps{
        echo "Committed to express-eks"
      }
    }
  }
}
