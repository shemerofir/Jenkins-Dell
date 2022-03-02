pipeline {
    agent any
    
    stages {
      
        stage('python script') {
             
            steps {
                 properties(
    [parameters([
        string(description: 'username', name: 'username', trim: true), 
        password(defaultValueAsSecret: <object of type hudson.util.Secret>, description: 'password', name: 'password')])
        ])
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



