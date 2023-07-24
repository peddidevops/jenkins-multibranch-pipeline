pipeline {
    agent none
    stages {
        stage('Hello Peddi-reddy') {
            steps {
                echo 'pddireddy welcome'
            }
        }
        stage('parallel') {
            parallel {
                stage('p-1') {
                    steps {
                        sh 'echo "peddireddy p-1"'
                    }
                }
                stage('p-2') {
                    steps {
                        sh 'echo "peddireddy p-2"'
                    }
                }
            }
        }
        stage('Hello Peddi') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
