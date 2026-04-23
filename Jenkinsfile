pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running tests using JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyzing code using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scanning with OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running Selenium tests on staging'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying to AWS EC2 production server'
            }
        }
    }
}
