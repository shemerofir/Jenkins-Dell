pipeline {
    agent any
    
    stages {
      
        stage('python script') {
              properties(
    [parameters([
        string(description: 'username', name: 'username', trim: true), 
        password(defaultValueAsSecret: <object of type hudson.util.Secret>, description: 'password', name: 'password')])
        ])
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



