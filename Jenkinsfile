pipeline {
    agent any

    stages {
        stage('Checkout'){
            steps {
                git branch: 'master',
                url: 'https://github.com/bhuvan-webknot/jenkins-handson/'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

        stage('Test'){
            steps {
                sh 'mvn test'
            }
        }

        stage('Deploy'){
            steps{
                echo "Successfully implemented the CI/CD pipeline... !!!"
            }
        }

    }
}