pipeline {
     agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh '''
                ls 
                mkdir myfolder
                cd myfolder 
                mkdir myfolder2
                ls
                '''
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