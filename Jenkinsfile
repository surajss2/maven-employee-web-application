pipeline {
    agent any

    stages {
        stage("checking Maven version") {
            steps {
                sh "mvn --version"
            }
        }
        stage("Clean the Target first") {
            steps {
                sh "mvn clean"
            }
        }
 
     }
    
}


