pipeline {
    agent any

    environment {
        MY_CREDENTIAL = credentials('ssh_test_id')
    }

    stages {
        stage ("hello") {
            
            steps {
                script {
                    echo '${MY_CREDENTIAL_USR}'
                }
            }
        }
    }
}