 pipeline{
         agent{label 'devops'}
         stages{
             stage('source'){
                 steps{
                     git https://github.com/zensoftllc/spring-petclinic.git'
                 }
             stage('package'){
                 steps{
                     sh 'mvn package'
                 }
             }
             }
         }
 }