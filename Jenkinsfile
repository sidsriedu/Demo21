pipeline {

    agent any

    stages {

        stage("build"){

            steps {
                echo 'Building the application'
            }

        }

        stage("test"){

            steps {
                echo 'Testing the application'
            }

        }

        stage("deploy"){

            steps {
                echo 'Deploying the application'
            }

        }
    }

    post {
        always {
            echo "post always"
        }
        success {
            echo "post success"
        }
        failure {
            echo "post failure"
        }
    }

}