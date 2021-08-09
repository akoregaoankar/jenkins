pipeline {
    agent { label 'linux' }
    stages {
        stage('First') {
            steps {
                sh '/tmp/myshell.sh'
            }
        }
        stage('Second') {
            steps {
                sh '/tmp/your-shell.sh'
            }
        }
    }
}
