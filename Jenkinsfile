pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'Hello World-dev'
                bat 'git clone "https://github.com/arorasugandhi/To-Do-List.git"'
            }
        }
        stage('QA') {
            steps {
                echo 'Hello World-QA'
            }
        }
        stage('UAT') {
            steps {
                echo 'Hello World-UAT'
            }
        }
        stage('pre-prod') {
            steps {
                echo 'Hello World-preprod'
            }
        }
        stage('prod') {
            steps {
                echo 'Hello World-prod'
            }
        }
    }
}
