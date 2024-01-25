pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo 'Cloning from git repo..'
                git 'https://github.com/nptran/web-app-flask.git'
            }
        }
    }
}