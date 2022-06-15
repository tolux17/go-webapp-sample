pipeline {
    agent any

    tools {

        go 'go-1.17'
    }

    environment {

        G0111MODULE='on'
    }

    stages {

        stage ("Test") {

            steps {
                
                git "https://github.com/tolux17/go-webapp-sample.git"
                

                sh 'go test ./...'
            }
        }
    }
}
