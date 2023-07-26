pipeline {
    agent any

    stages {
        stage('Hello Peddi') {
            steps {
                echo 'Hello World'
                sh 'sleep 10'
            }
        }
        stage('paralalle'){
            parallel {
                stage('p-1'){
                    steps {
                        sh 'echo "p-1"'
                        sh 'sleep 10'
                    }
                }
                stage('p-2'){
                    steps {
                        sh 'echo "p-2"'
                        sh 'sleep 10'
                    }
                }
            }

        }
        stage('jana') {
            steps {
                echo 'jana'
                sh 'sleep 10'
            }
        }
    }
}
