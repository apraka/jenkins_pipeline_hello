pipeline {
    agent any
    stages {
        stage('clone my code'){
          git 'https://github.com/apraka/maven-project/'
          }
         stage ('compile my code'){
            steps {
                withMaven(maven : 'local maven'){
                  sh `mvn compile`
                  }
                 }
                }
               }
              } 
