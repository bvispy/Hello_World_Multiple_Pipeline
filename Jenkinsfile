pipeline {
    agent any
    stages {
        
        stage('build') {
            steps {
                sh mvn 
                sh 'echo "mvn --version"'
            }
        }
        

        stage('test') {
            steps {
                sh 'echo "TESTING"'
            }
        }
    
        stage('DEv') {
            steps {
                sh 'echo "DEV"'
            }
        }
    }
}
