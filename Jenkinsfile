pipeline {
  agent any
  stages {
    stage {'Build'}
    steps {
      echo  'Running build automation'
      sh './gradlew build --no-demeon'
        ArchiveArtifacts artifacts: 'dist/trainSchedule.zip'  
    }
  }
}
}
