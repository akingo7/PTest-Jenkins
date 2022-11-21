pipeline {
    agent {
        label 't2micro-ubuntu'
    }
    parameters {
    string(name: 'PERSON', defaultValue: 'Gabriel', description: 'Who should I say hello to?')
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello ${PERSON}"'
            }
        }
    }
}