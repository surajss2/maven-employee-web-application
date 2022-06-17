pipeline {
    agent any

    stages {
        stage("compile the Maven") {
            steps {
                sh "mvn clean compile"
            }
        }
        stage("package") {
            steps {
                sh "mvn clean install"
            }
        }
 
     }
    
}

