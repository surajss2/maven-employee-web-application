pipeline {
    agent any

    stages {
 //       stage('git checkout') {
 //           steps {
 //               git 'https://github.com/surajss2/maven-webapp_Helloworld.git'
            }
        }
        
    //    stage('reading pom.xml file') {
    //        steps {
    //          readMavenPom file: 'my-app/pom.xml'
    //        }
    //  }
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
 //       stage("Deploy") {
 //           steps {
 //               deploy adapters: [tomcat8(credentialsId: 'tomcat_local', path: '', url: 'http://localhost:8082')], contextPath: '/webapp', war: 'target/*.war'
 //           }    
 //       }
    }
    
}


