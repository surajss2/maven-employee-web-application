pipeline {
    agent any

    stages {
        stage("build maven") {
            steps {
                sh "mvn clean compile"
            }
        }
        stage("package") {
            steps {
                sh "mvn package"
            }
        }
 
     }
    
}


