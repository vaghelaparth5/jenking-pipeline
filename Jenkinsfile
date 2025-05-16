pipeline {
    agent any  // Runs on any available agent

    stages {
        // Stage 1: Build 
        stage('Build') {
            steps {
                echo 'Simulating build...'
                sh 'echo "No build tool required for this example"'
            }
        }

        // Stage 2: Unit and Integration Tests
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running simulated tests...'
                sh 'echo "No tests configured yet"'
            }
        }

        // Stage 3: Code Analysis
        stage('Code Analysis') {
            steps {
                echo 'Running SonarQube scan...'
                sh 'echo "Simulating SonarQube analysis"'
            }
        }

        // Stage 4: Security Scan
        stage('Security Scan') {
            steps {
                echo 'Running OWASP Dependency-Check...'
                sh 'echo "Simulating security scan"'
            }
        }

        // Stage 5: Deploy to Staging
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to AWS EC2 staging...'
                sh 'echo "Simulating deployment to staging"'
            }
        }

        // Stage 6: Integration Tests on Staging
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running Postman/Selenium tests...'
                sh 'echo "Simulating staging tests"'
            }
        }

        // Stage 7: Deploy to Production
        stage('Deploy to Production') {
            steps {
                echo 'Deploying to AWS EC2 production...'
                sh 'echo "Simulating production deployment"'
            }
        }
    }
}