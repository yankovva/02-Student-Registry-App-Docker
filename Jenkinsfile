pipeline{
    agent any
    stages {
        stage('NPM Install'){
            steps{
                sh 'npm install'
            }
        }
        stage('NPM Install'){
            steps{
                sh 'npm run test'
            }
        }
    }
}