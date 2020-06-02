 pipeline{
         agent{label 'devops'}
         stages{
             stage('Source'){
                 steps {
                     git 'https://github.com/PanduRamdaspally/spring-petclinic-1.git'
                 }
             }
             stage('package'){
                 steps {
                     sh 'mvn package'
                 }
             }
             }
         }
