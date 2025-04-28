pipeline {
    agent any
    stages {
        stage('branch') {
            steps {
                echo 'in the process'
                echo "${env.BRANCH_NAME}"
                bat 'hello.bat'
            }
        }
    }
}
