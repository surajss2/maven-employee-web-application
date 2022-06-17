pipeline {
    agent none 
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello, Maven'
                sh 'mvn clean'
            }
        }
        stage('Example package') 
            steps {
                echo 'Hello, Maven'
                sh 'mvn package'
            }
        }
    }
}
