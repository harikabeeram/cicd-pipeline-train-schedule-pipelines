pipeline {
  agent any
   stages {
    stage ('build') {
     steps{
      echo 'Running build an automation'
      sh './gradlew build --no-deamon'
      archiveArtifacts artifacts: 'dist/trainScheduler.zip'
     }
    }
   }
}
