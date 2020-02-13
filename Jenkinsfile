pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello debraj!"
                sh "echo Hello from the shell"
                sh "hostname"
                sh "uptime"
            }
        }
    }
}
