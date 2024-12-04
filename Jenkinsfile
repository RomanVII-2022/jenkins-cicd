pipeline {
    agent any

    environment {
        MY_CREDENTIAL = credential('project-one-id')
    }

    stages {
        stage ("hello") {
            
            steps {
                script {
                    echo "${MY_CREDENTIAL}"
                }
            }
        }
    }
}