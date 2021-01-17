pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
				echo "Build"
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
