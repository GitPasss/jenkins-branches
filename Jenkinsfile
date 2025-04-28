pipeline {
    agent any
    stages {
        stage('branch') {
            steps {
                echo 'in main the process'
                echo "${env.BRANCH_NAME}"
                bat 'hello.bat'
            }
        }
    }
}
