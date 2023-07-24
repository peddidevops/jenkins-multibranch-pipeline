pipeline {
    agent none
    stages {
        stage('Hello-peddi') {
                    steps {
                        echo "hellow peddi"
                    }
                }
        stage('parallel-one') {
            parallel {
                stage('parallel-1') {
                    steps {
                        sh 'echo "peddiredy welcome"'
                    }
                }
                stage('Parallel-2') {
                    steps {
                        sh '''
                        echo "jana"
                        pwd
                        touch peddi.txt
                        ls
                        '''
                    }
                }
            }
        }
        stage('Hello-peddireddy') {
                    steps {
                        echo "hellow peddi jana"
                    }
                }
    }
}
