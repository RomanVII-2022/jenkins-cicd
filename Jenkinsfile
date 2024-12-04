pipeline {
    agent any

    environment {
        MY_CREDENTIAL = credentials('project-one-id')
    }

    stages {
        stage ("hello") {
            
            steps {
                script {
                    echo "${MY_CREDENTIAL_USR}"
                }
            }
        }
    }
}