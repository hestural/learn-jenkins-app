pipeline {
    agent any

    
    stages {
        
        stage('Test'){
            steps{
                echo 'Testing the new laptop ...'
                sh '''
                    test -f build/public/index.html
                '''
            }
        }
    }
}