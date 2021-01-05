Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build-test') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}