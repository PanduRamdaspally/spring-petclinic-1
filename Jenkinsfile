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

