pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Set Permissions') {
            steps {
                sh 'chmod +x ls_script.sh'
            }
        }
        stage('Run Script') {
            steps {
                sh './ls_script.sh'
            }
        }
    }
}
