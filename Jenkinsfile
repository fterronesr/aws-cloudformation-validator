pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                sh 'echo "hola mundo"' 
            }
        }
        stage('Test'){
            steps {
                sh 'echo "TEST"'
                
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploy"'
            }
        }
    }
}