pipeline {
    agent { label 'linux' }
    stages {
        stage('test') {
            steps {
                  echo "Pipeline output" >> /tmp/pipeline.txt
            }
        }
    }
}
