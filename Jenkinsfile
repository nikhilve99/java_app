@Library('nik-shared-lib') _
pipeline {
    agent any
    stages{
        stage('Git Checkout'){
            steps {
           git branch: 'master', url: 'https://github.com/nikhilve99/node_hello_world.git'
            }
        }
        stage('unit test case'){
            steps {
                script{
                    npmTest()
                }                
            }
        }
    }
}