pipeline {
    agent {
        label 'slave-7'
    }
    //agent any
    //agent none
    stages {
        stage('BUILD') {
            steps {
                echo "This is Build Stage"
                sh 'hostname'
                echo "Running on ${env.NODE_NAME}"
                sh 'sleep 5'
            }
        }

        stage('TEST') {
            steps {
                echo "This is Test Stage"
                sh 'sleep 5'
            }
        }

        stage('DEPLOY') {
            steps {
                echo "This is Deploy Stage"
                sh 'sleep 5'
            }
        }
    }
}
