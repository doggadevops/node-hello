pipeline {
    agent any 

    stages {

        stage("Build Node App"){

            steps {

                script {
                    sh "npm install"
                }

            }

        }

        stage("Run Code Analysis"){

            steps {

               echo "Run Code Analysis"

            }

        }

        stage("Push Artifacts"){

            steps {

               echo "Push  Artifacts"

            }

        }

        stage("Deploy to Dev"){

            steps {

               echo "Deploying to Dev....."

            }

        }

        stage("Deploy to UAT"){

            steps {

                echo "Deploying to UAT....."

            }
        }

        stage("Deploy to PROD"){

            steps {

                echo "Deploying to PROD....."

            }
        }

    }
}
