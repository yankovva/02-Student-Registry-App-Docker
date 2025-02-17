pipeline{
    agent any
    stages {
        stage('NPM Install'){
            steps{
                echo 'npm install'
            }
        }
        stage('NPM audit test'){
            steps{
                echo 'npm audit'
            }
        }
        stage('Run  integration tests'){
            steps{
                echo 'npm run test'
            }
        }
        
    }
}