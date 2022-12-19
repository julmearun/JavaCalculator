pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh 'mvn build'
            }
        }
        stage ('compile') {
             steps {
                sh 'mvn compile'
          }
        }
    }
}
