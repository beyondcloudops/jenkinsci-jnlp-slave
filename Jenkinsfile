node ('slave'){
        stage('Checkout') {
                checkout scm
                build()
                deploy()
        }
        def build(){
                stage "SCM checkout"
                sh 'ls -la'
        }
        def deploy(){
                stage "deploy"
        sh 'whoami'
        }  
}
