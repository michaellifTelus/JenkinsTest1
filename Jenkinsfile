pipeline {
    agent { node { label 'agent' } }
    stages {
        stage('Build, Unit test, Static code analysis') {
            steps {
                sh './gradlew build --stacktrace --scan'
            }
        }
    }
}
