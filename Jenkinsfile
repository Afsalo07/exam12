pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/Afsalo07/exam12.git'
            }
        }

        stage('Show File') {
            steps {
                bat 'type age.html'
            }
        }
    }
}
