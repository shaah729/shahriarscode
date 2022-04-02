pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                echo 'building the application1'
            }
        }
      
       stages {
        stage('test') {
            steps {
                sh 'mvn --version'
            }
        }
         
          stages {
        stage('deploy') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
