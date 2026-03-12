pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/Afsalo07/exam12.git'
            }
        }

        stage('Show File') {
            steps {
                sh 'cat age.html'
            }
        }
    }
}
