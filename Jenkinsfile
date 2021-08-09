pipeline {
    agent { lable 'linux' }
    stages {
        stage('First') {
            steps {
                echo 'My Pipeline created'
            }
        }
        stage('Second') {
            steps {
                sh '/tmp/one-script.sh'
            }
        }
    }
}
