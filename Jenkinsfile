pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh "touch abc"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                 "touch abc"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh "touch abc"
            }
        }
    }
     post {
       failure {
	 echo "Failed"
           
       }
       success {
	 echo "success"
           
       }
    }
}