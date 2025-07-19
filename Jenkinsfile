pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning source code...'
            }
        }

        stage('Compile Java') {
            steps {
                echo 'Compiling HelloWorld.java...'
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run Java') {
            steps {
                echo 'Running HelloWorld class...'
                sh 'java HelloWorld'
            }
        }
    }
}
