@Library('nik-shared-lib')
pipeline {
    agent any
    stages{
        stage('Git Checkout'){
            steps {
                    gitCheckout(
                        branch: "main",
                        url: "https://github.com/nikhilve99/java_app.git"
                    )
            }
        }
    }
}