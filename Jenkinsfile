pipeline {
    agent any

    stages {
        stage('NPM Build') {
          steps {
			bat "npm cache clean --force"
			bat "npm install -g npm@latest --force"
			bat "npm cache clean --force"
            bat "npm install"
            bat "npm start"
          }
        }
    } 
}