pipeline{
    agent any
    tools {
            maven 'MAVEN_HOME'
          }

    stages{
        stage('Build'){
            sh 'mvn clean package'
        }

    }


}
