pipeline {
    agent any
    tools {
        git 'Default'  // Replace 'Default' with the Git tool name configured in Jenkins
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
    }
}

