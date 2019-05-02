node ('slave'){
        stage('Checkout') {
                checkout scm
                sh 'ls -la'
                sh 'whoami'       
        }
        stage('Build Docker Image') {
                deleteDir()
                sh 'make build'
        }
}
