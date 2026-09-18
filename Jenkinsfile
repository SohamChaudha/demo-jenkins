pipeline {
    agent any 
    stages {
        stage ("Test") {
            steps {
                sh "echo Running Tests...."
            }
        }
        stage ("Approve") {
            steps {
                input message: "Test passed. Deploy to production ?"
            }
        }
        stage ("Deploy") {
            steps {
                sh "echo Deploying to production"
            }
        }
    }
}
