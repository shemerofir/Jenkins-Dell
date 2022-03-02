pipeline {
    agent any
    
 parameters {
        string(name: 'PARAM1', description: 'Param 1?')
        string(name: 'PARAM2', description: 'Param 2?')
    }
        
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



