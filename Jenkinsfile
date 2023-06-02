@Library('nik-shared-lib') _
pipeline {
    agent any
    stages{
        stage('Git Checkout'){
            steps {
           git branch: 'Dev', url: 'https://github.com/nikhilve99/java_app.git'
            }
        }
        stage('unit test case'){
            steps {
                script{
                    mvnTest()
                }
            }
        }
    }
}