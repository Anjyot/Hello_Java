pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                echo 'git branch: 'main', credentialsId: '0313d9f0-8a5c-4846-9b09-9ef0d2dd7952', url: 'https://github.com/Anjyot/Hello_Java.git''
            }
        }
        stage('Compile') {
            steps {
                bat 'javac Main.java'
            }
        }
        stage('Run') {
            steps {
                bat 'java Main'
            }
        }
    }
}
