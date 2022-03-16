pipeline {
    agent any
    stages {
        stage('Jmeter TEST') {
            steps {
                sh "./mvnw verify -Pperformance"
            }
        }
    }
}
