pipeline{
  agent any 
  stages{
    stage('Bomanai'){
      steps{
         sh 'sudo pip install --no-cache-dir --upgrade boman-cli'
         sh 'sudo ~/.local/bin/boman-cli -a run -cicd jenkins'
      }
    }
  }
}
