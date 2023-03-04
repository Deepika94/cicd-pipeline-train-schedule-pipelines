pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo ' Running build automation '
        sh './gradlew build --no-deamon'
        archieveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
  
  
