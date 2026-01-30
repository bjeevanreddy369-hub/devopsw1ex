pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/bjeevanreddy369-hub/devopsw1ex.git'
            }
        }

        stage('Build') {
            steps {
                sh 'javac Hello.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Hello'
            }
        }
    }
}
