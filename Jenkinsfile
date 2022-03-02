pipeline {
    agent any
    
    stages {
      
        stage('python script') {
             
            steps {
                 properties(
    [parameters([
        string(description: 'username', name: 'username', trim: true)])
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



