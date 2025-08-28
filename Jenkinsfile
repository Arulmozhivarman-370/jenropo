pipeline {
    agent any

    stages {
        stage('built') {
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
        stage('deploy'){
            steps{
                echo "hello deploy stage"
                sh 'date'
            }
        }
    }
}
