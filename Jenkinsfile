pipeline {
    agent any
    properties(
        [parameters([
        string(description: 'username', name: 'username', trim: true), 
        password(defaultValueAsSecret: <object of type hudson.util.Secret>, description: 'password', name: 'password')])
        ]
        )
    stages {
        stage('python script') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}



