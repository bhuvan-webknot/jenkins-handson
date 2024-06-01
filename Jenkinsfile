pipeline {
    agent any

    stages {
        stage('Checkout'){
            steps {
                git branch: 'master',
                credentialsId: '4fd2c8fd-4db2-431a-aded-69080c947edf'
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