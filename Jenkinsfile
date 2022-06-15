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
                

                sh 'go test ./...'
            }
        }
    }
}
