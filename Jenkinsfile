pipeline {
    agent any
    stages{
        stage('Git Checkout'){
            steps {
                script {
                    git branch: 'Dev', credentialsId: 'token_key_github', url: 'https://github.com/nikhilve99/java_app.git'
                }
            }
        }
    }
}