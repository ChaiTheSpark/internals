pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git url: "https://github.com/ChaiTheSpark/internals.git", branch: "main"
            }
        }

        stage('Run Script') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }

        stage('Run Python Script') {
            steps {
                sh 'chmod +x chaithu.py'
            }
        }

    }
}
