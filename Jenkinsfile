pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh "${tool name: 'sbt'}/bin/sbt compile"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
