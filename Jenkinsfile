pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/mani031298/gitpractise.git'
            }
        }

        stage('Build') {
            steps {
                echo "No build for HTML project"
            }
        }

        stage('Archive') {
            steps {
                archiveArtifacts artifacts: '**/*', allowEmptyArchive: true
            }
        }
    }
}
