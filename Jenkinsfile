pipeline {
    agent any

    stages {
        stage('Hello Peddi') {
            steps {
                echo 'Hello World'
            }
        }
        stage('paralalle'){
            parallel {
                stage('p-1'){
                    steps {
                        sh 'echo "p-1"'
                    }
                }
                stage('p-2'){
                    steps {
                        sh 'echo "p-2"'
                    }
                }
            }

        }
        stage('jana') {
            steps {
                echo 'jana'
            }
        }
    }
}
