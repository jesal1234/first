pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                bat 'javac Helloworld.java'
            }
        }
        stage('build') {
            steps {
                echo 'building in progress'
            }
        }
        stage('test') {
            steps {
                echo 'testing in progress'
            }
        }
        stage('deploy') {
            steps {
                echo 'deployment completed'
                bat 'java Helloworld'
            }
        }
    }
}
