pipeline {
    agent any
    stages{
        stage('checking python version') {
            steps {
                bat 'python -V'
            }
        }

        stage('REPO Cloning'){
            steps {
                bat 'xcopy /S "*" "C:/xampp/htdocs" /Y'
            }
        }

        stage('Print done'){
            steps{
                echo 'Done!'
            }
        }
    }
}
