pipeline {
    agent any
    
    [parameters([
        string(description: 'username', name: 'username', trim: true)])]
        
    stages {
      
        stage('python script') {
             
            steps {
                 echo 'Testing..'
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



