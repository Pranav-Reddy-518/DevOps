pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git branch: 'devopscsea',url: 'https://github.com/Pranav-Reddy-518/DevOps.git'
            }
        }
        stage('Build') {
            steps {
                sh 'javac Helloo.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java Helloo'
            }
        }
    }
}
