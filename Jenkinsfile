pipeline {
    agent any

    stages {
        stage("maven package") {
            steps {
                sh "mvn package"
            }
        }
        stage("deploy the war file") {
            steps {
                sh "mvn deploy"
            }
        }
 
     }
    
}

