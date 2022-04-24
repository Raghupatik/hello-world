pipeline {
    agent any

    stages('CI') {
       stage(''){
            steps {
                echo "Checkout"
                checkout scm
            }
        }

       stage('build'){
            steps {
                echo "Build"
                sh 'mvn clean build'
            }
        }

        stage('Test'){
            steps {
                echo "Test"
                sh 'mvn test'
            }
        }

    }
}