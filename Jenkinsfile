pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Stage : Cloning the Git repo ......'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Stage : Building the Code ......'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Stage : Testing the Code ......'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Stage : Deploying to Server ......'
            }
        }
    }
}
