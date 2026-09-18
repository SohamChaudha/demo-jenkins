pipeline {
    agent any
    parameteres {
        string(name: "VERSION" , defaultValue: "1.0" , description: "Version to deploy")
        choice(name: "ENVIRONMENT" , choices: ["staging" , "production"] , description: "Target")
        booleanParam(name: "SKIP_TEST" , defaultValue: false , description: "Skip Test ?")
    }
    stages {
        stage ("Build") {
            steps {
                echo "Building...."
            }
        }
    }
}
