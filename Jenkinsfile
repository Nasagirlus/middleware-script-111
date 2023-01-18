pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
                zip  zip middlewasreScript$-{BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md 
            }
        }
        
    }
}