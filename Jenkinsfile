pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh "rm -rf testrepo" 
                sh "git clone https://github.com/ardekanian/testrepo.git"
                sh "mvn clean -f testrepo/pom.xml"
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy'
            }
        }
    }
}
