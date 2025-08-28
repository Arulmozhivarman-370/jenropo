pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                echo 'Hello built stage'
                sh 'pwd'
            }
        }
        stage('test'){
            steps{
                echo "hello test stage"
                sh 'hostname'
            }
        }
        stage('package') {
            steps {
                echo 'Hello pacakage stage'
                sh 'pwd'
            }
        }
        stage('deploy'){
            steps{
                echo "hello deploy stage"
                sh 'hello world'
            }
        }
    }
}
