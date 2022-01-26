pipeline {
    agent any

    stages {
        stage('NPM Build') {
          steps {
			bat "cd jinkinstest"
            bat "npm install -d"
            bat "npm start"
          }
        }
    } 
}