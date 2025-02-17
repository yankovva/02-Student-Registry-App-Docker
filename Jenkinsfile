pipeline{
    agent any
    stages {
        stage('NPM Install'){
            steps{
                sh 'npm install'
            }
        }
        stage('Run tests'){
            steps{
                sh 'npm run test'
            }
        }
    }
}