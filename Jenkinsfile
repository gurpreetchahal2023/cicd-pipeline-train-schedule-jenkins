pipeline{
  agent any
  stages{
    stahe ('Build) {
           steps{
             
             echo 'Running guild automation'
             sh './gradlew build --no-daemon'
             archiveArtifacts artifacts: 'dist/trainSchedule.zip'
           }
         
           
    }
    
  }
}
