pipeline{
    agent any
      tools {
        maven 'Maven-tool'
            }

    stages{
        stage('Build'){
         steps{
             sh 'mvn clean install'
            }
        }

    }


}
