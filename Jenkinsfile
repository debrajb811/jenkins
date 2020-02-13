pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello me Debraj!"
                sh "echo Hello from the shell"
                sh "hostname"
                sh "uptime"
            }
        }
    }
}
