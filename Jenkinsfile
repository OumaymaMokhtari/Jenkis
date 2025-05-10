pipeline {
    agent any

    stages {
        stage('Afficher la version Docker') {
            steps {
                sh 'docker --version'
            }
        }

        stage('Lancer hello-world') {
            steps {
                sh 'docker run hello-world'
            }
        }
    }
}

