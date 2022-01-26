pipeline {
    agent any

    stages {
        stage('NPM Build') {
          steps {
            bat "npm install -d"
            bat "npm start"
          }
        }
    } 
}
