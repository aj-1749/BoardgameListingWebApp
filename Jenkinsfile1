pipeline {
    agent any 
    
    tools {
        maven 'maven3'
        jdk 'jdk17'
    }
    
    environment {
        SCANNER_HOME= tool 'sonar-scanner'
    }

    stages {        
        stage('Compile') {
            steps {
                sh "mvn compile"
            }
        }
        
    }
}
