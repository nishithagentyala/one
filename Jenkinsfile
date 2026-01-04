pipeline {
    agent any

    tools {
        maven 'maven'
    }

    stages {

        stage('Code') {
            steps {
                git 'https://github.com/nishithagentyala/one.git'
            }
        }

        stage('Build') {
            steps {
                sh "mvn clean package"
            }
        }
    }
}
