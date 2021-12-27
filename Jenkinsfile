pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh '.gradlew vuild --no-daemon'
        archiveArtifacts artiacts 'dist/trainSchedule.zip'
      }
    }
  }
}
