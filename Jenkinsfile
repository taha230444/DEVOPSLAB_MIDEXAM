pipeline {
    agent any

    stages {
        stage('Install Dependencies') {
            steps {
                echo 'Installing dependencies...'
                // Example command to install dependencies
                sh 'echo "Dependencies installed."'
            }
        }
        stage('Run Tests') {
            steps {
                echo 'Running tests...'
                // Example command to run tests
                sh 'echo "Tests passed."'
            }
        }
        stage('Archive Artifacts') {
            steps {
                echo 'Archiving artifacts...'
                // Example command to archive artifacts
                archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true
            }
        }
    }
}
