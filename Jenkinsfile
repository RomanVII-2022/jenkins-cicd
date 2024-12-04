pipeline {
    agent any

    stages {
        stage ("hello") {
            when {
                env.BRANCH_NAME == "main"
            }
            steps {
                script {
                    echo env.BRANCH_NAME
                }
            }
        }
    }
}