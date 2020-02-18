pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
                sh "echo Hello from the Shell"
                sh "hostname"
                sh "uptime"
            }
        }
    }
}
