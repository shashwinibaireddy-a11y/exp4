pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
