pipeline {
    agent any 
    stages {
        stage ('Build') {
            steps {
                echo "***** Building the application *********"
            }
        }
        stage ('Sonar') {
            steps {
                echo "***** Building the application *********"
            }
        }
        stage ('DockerBuild') {
            steps {
                echo "***** Building the Container application *********"
            }
        }
        stage ('DockerPus') {
            steps {
                echo "***** Pushing  the image *********"
            }
        }
        stage ('DeployToDev') {
            steps {
                echo "***** Deploying  the application to dev env *********"
            }
        }
        stage ('DeployToTest') {
            steps {
                echo "***** Deploying  the application to test env *********"
            }
        }
        stage ('DeployToStage') {
            steps {
                echo "***** Deploying  the application to Stage env *********"
            }
        }
        stage ('DeployToProd') {
            input {
                message "Ready to deploy in prod ?"
                ok 'yes'
                submitter 'i27academy' // ad or jenkins database.. username
            }
            steps {
                echo "***** Deploying  the application to dev env *********"
            }
        }
    }
}
