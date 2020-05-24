pipeline {
    agent any
    environment {
        AWS_SECRET = credentials('Secrettxt')
        BIT_BKT_CREDS = credentials('test101')
        }        

    stages {
        stage('Example') {
            steps {
                echo "Running on ${env.BRANCH_NAME}, Build Number${env.BUILD_ID} on ${env.JENKINS_URL}"
                echo "The encrypted password is ${AWS_SECRET}"
                echo "The Username and password is ${BIT_BKT_CREDS}"
            }
        }
    }
}
