pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "Running on ${env.BRANCH_NAME}, Build Number${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
