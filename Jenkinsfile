pipeline {
    agent any
    stages {
        stage("Checkout") {
            steps {
                git branch: 'main', url: 'https://github.com/bhuvaneshcmd/jenkins-webhook.git'
            }
        }
    }
}
