pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sbt new playframework/play-scala-seed.g8
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
