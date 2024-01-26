pipeline {
    agent any
    stages {
        stage('Compile code') {
            steps {
                echo "Compiling the program....."
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run code') {
            steps {
                echo "Running the program....."
                sh 'java HelloWorld'
            }
        }
    }
}

