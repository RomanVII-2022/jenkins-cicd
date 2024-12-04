pipeline {
    agent any

    stages {
        stage ("hello") {
            
            steps {
                script {
                    echo env.BRANCH_NAME
                }
            }
        }
    }
}