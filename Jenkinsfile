node ('jnlp'){
        stage('Checkout') {
                checkout scm
                sh 'ls -la'
                sh 'whoami'       
        }
        stage('Build Docker image') {
                sh 'make build'
        }
}
