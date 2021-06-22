pipeline {
    agent any
    
    environment {
        PROJECT_NAME = "NEPTUN"
        OWNER_NAME = "ini ikrini"
    }
    
    
    stages {
        stage('1-Build') {
            steps {
                echo "Start of Stage Build"
                echo "Building......."
                echo "end of Stage Build"
            }
        }
    
        stage('2-Test') {
            steps {
                echo "Start of Stage Test"
                sh "ls -la"
                echo "Testing......."
                echo "Hello ${OWNER_NAME}"
                echo "Poject name is ${PROJECT_NAME}"
                echo "end of Stage Build"
            }
        }
    
        stage('3-Deploy') {
            steps {
                echo "Start of Stage Deploy"
                echo "Delploying......."
                sh '''
                    echo "Line1"
                    echo "Line2"
                 
                '''
                echo "end of Stage Build"
            }
        }
        
        stage('4-Celebrate') {
           steps {
            echo "CONGRATULATIONS!"
           }
        }
    }
    
    
}
