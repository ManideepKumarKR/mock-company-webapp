pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // TODO: Add build step
                script {
                    sh './gradlew assemble'
                }
            }
        }

        stage('Test') {
            steps {
                // TODO: Add test step
                script {
                    sh './gradlew test'
                }
            }
        }
    }

    post {
        always {
            // TODO: Add post-build actions
            script {
                // This can be used for cleanup or additional actions after the build/test stages
            }
        }
    }
}
