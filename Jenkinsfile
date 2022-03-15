pipeline {
    agent any
    stages {
        stage('Jmeter TEST') {
            steps {
                sh "mvn verify -Pperformance"
            }
        }
    }
}
