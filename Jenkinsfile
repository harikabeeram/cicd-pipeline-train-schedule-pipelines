pipeline {
  agent any
   stages {
    stage ('build') {
     steps{
      echo 'Running build an automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainScheduler.zip'
     }
    }
   }
}
