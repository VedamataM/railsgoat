pipeline{
  agent any 
  stages{
    stage('Bomanai'){
      steps{
         sh 'sudo pip install --extra-index-url https://test.pypi.org/simple/ boman-cli-uat==14.1'
         sh 'sudo ~/.local/bin/boman-cli-uat -a run -cicd jenkins'
      }
    }
  }
}
