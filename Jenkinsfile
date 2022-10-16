pipeline {
    agent any

    stages {
        stage('Hello1') {
            steps {
                echo 'Helloworld..'
            }
        }
        stage('sleep') {
            steps {
                sh 'sleep 30'
            }
        }
        stage('Hello2') {
            steps {
                echo 'HelloDevops....'
            }
        }
    }
}
