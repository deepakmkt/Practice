pipeline {
    agent any
    tools {
        git 'Default' // Use the default Git installation
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
    }
}
