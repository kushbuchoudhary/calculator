pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/kushbuchoudhary/calculator.git'
            }
        }

        stage('Compile') {
            steps {
                sh 'javac Calculator.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Calculator 25 5'
            }
        }

    }
}
