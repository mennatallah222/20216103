pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        
        stage('Run Script') {
            steps {
                sh './ls_script.sh'
            }
        }
    }
}
