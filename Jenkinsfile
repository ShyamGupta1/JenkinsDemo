pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building on Windows...'
            }
        }

        stage('Run Script') {
            steps {
                echo 'Displaying contents of hello.txt'
                bat 'type hello.txt'
            }
        }

        stage('Finish') {
            steps {
                echo 'Pipeline complete.'
            }
        }
    }
}
