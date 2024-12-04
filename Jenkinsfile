pipeline {
    agent any

    stages {
        stage ("hello") {
            
            steps {
                script {
                    echo echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL} branch name ${env.BRANCH_NAME}"
                }
            }
        }
    }
}