node ('slave'){
        stage('Checkout') {
                checkout scm
                build
                deploy()
        }
        def checkout{
                sh 'ls -la'
        }
        def deploy(){
        sh 'whoami'
        }  
}
