pipeline {
    agent any

    stages {
        stage("Clone Repository") {
            steps {
                git 'https://github.com/mamatha-19/demo2_rep.git'
            }
        }
        stage('Build') {
            steps {
                sh 'javac hello.java'
            }
        }
        stage('run') {
            steps {
                sh 'java hello'
            }
        }
    }
}
