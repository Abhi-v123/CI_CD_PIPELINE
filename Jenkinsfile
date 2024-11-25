pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Abhi-v123/ci_cd_pipeline.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add your build commands here (e.g., 'sh build.sh')
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test commands here (e.g., 'sh test.sh')
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Add your deployment commands here (e.g., 'sh deploy.sh')
            }
        }
    }
}
