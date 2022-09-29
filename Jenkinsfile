pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo "maven build"
                sh 'mvn clean install'
            }
        }
        stage('deploy') {
            steps {
                echo "Color ${params.color}"
            }
        }
        stage('build-test') {
            steps {
                sh "docker --version"
                echo "test:color"
            }
        }
    }
}
