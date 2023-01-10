pipeline {
    agent any 
    stages {
        
        stage ('check out') {
            steps {
               git 'https://github.com/julmearun/JavaCalculator.git'
            }
        }
        stage('Build') { 
            steps {
                sh 'mvn build' 
            }
        }
        stage('Test') { 
            steps {
                sh 'mvn test'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'mvn deploy' 
            }
        }
    }
}
