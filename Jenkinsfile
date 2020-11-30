#!groovy

pipeline {
 agent any
  tools {
        //env.M2_HOME = tool name: 'Maven 3.2', type: 'maven'
        maven 'Maven3.6.3'
        }
       
  stages{
       
        stage('SFDA Workflow Engine Code Checkout') {
            steps {
                echo "Cleaning the workspace before checkout"  
                cleanWs()
                git branch: "main", credentialsId: 'sfdaPipe', url: 'https://github.com/jcvalladares/xtreamteam.git'
            }
        }
       
       
        stage('Code Building and Unit Test suite') {
            steps {
                script {    
                        sh "${env.M2_HOME}/bin/mvn -f ${env.WORKSPACE}/sfda/pom.xml clean install"
                }

            }
        }
   
        stage('Deploy') {
            steps {
                echo "Attempting to deploy"
                script {    
                        sh "usr/bin/java -jar ${env.WORKSPACE}/sfp-build-pipeline/sfda/target/sfda-0.0.1-SNAPSHOT.jar"
                }

            }
        }

      }
     
}
