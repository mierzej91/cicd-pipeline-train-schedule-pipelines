
pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh './gradlew build'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip', onlyIfSuccessful: true

            }
        }

    }
}
