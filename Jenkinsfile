 pipeline{
         agent{label 'devops'}
         stages{
             stage('Source'){
                 steps {
                     git 'https://github.com/zensoftllc/spring-petclinic.git'
                 }
             }
             stage('package'){
                 steps {
                     sh 'mvn package'
                 }
             }
             }
         }



pipeline {
    agent {label 'MASTER'}
    stages {
        stage('Source'){
            steps {
                git 'https://github.com/dummyrepos/spring-petclinic.git' 
            }
        }
        stage('Package'){
            steps {
                sh 'mvn package'
            }
        }
    }
}