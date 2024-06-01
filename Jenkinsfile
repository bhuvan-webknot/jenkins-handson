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
                echo 'This is the build stage'
            }
        }

        stage('Test'){
            steps {
                echo 'This is the testing stage'
            }
        }

        stage('Deploy'){
            steps{
                echo "Successfully implemented the CI/CD pipeline... !!!"
            }
        }

    }
}