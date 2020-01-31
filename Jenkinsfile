pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script{
                    echo 'Build...'
                    sh './build.sh ${env.BRANCH_NAME}'
                }
            }
        }
    }
}
