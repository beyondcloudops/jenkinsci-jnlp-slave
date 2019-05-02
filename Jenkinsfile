node ('slave'){
        stage('Checkout') {
                build
                deploy()
        }
        def checkout{
        checkout scm
        }
        def deploy(){
        whoami
        }  
}
