pipeline {
    agent {
        label 'slave-7'
    }
    stages {
        stage('BUILD') {
            steps {
                echo "This is Build Stage"
                sh 'hostname'
                echo "Running on ${env.NODE_NAME}"
            }
        }

        stage('TEST') {
            steps {
                echo "This is Test Stage"
            }
        }

        stage('DEPLOY') {
            steps {
                echo "This is Deploy Stage"
            }
        }
    }
}
