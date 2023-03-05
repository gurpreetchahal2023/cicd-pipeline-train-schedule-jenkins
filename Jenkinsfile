pipeline{
  agent any
  stages{
    stage ('Build) {
           steps{
             
             echo 'Running guild automation'
             sh './gradlew build --no-daemon'
             archiveArtifacts artifacts: 'dist/trainSchedule.zip'
           }
         
           
    }
    
  }
}
