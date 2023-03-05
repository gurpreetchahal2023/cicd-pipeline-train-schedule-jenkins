pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
             echo 'Running guild automation'
             sh './gradlew build --no-daemon'
             archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
