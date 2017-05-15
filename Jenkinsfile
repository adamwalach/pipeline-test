pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'cowsay -f tux If you build it they will come'
            }
        }
        stage('Test'){
            steps {
                sh 'cowsay -f dragon You shall not pass'
            }
        }
        stage('Deploy') {
            steps {
                sh 'cowsay -f turtle Ship to production!'
            }
        }
    }
}
