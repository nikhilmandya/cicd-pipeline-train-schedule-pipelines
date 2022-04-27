pipeline {
  agent any
  stages {
    stage('Build'){
      steps {
          echo 'Running build automation'
          sh './gradlew build --no-daemon' #not a good ideal situation for jenkins pipeline
          archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        
      }
    
    }
  
  }
}
