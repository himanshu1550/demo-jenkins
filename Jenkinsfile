pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Perform the build steps here
                // For example: compiling code, running tests, etc.
                echo 'Building...'
            }
        }

        stage('Deploy') {
                            input {
                    message 'Press "Proceed" to deploy'}
            steps {
                sh   " echo Deploying with key:"

            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
