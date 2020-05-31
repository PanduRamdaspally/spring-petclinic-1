## Scripted pipeline
#node {
 #   stage('scm'){
  #      git 'https://github.com/zensoftllc/spring-petclinic.git'
   # }
   # stage('build'){
   #     sh 'mvn package'
   # }
#}
#}
## Declarative pipeline
 pipeline
     {
         Stages{
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
     