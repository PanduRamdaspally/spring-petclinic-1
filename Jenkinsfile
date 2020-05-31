 pipeline{
         agent{label 'devops'}
         stages{
             stage('source'){
                 steps{
                     git 'https://github.com/zensoftllc/spring-petclinic.git'
                 }
             stage('package'){
                 steps{
                     sh 'mvn package'
                 }
             }
             }
         }
<<<<<<< HEAD
 }
=======
     
>>>>>>> e6a670022eb099d373e78087b8042466e93127f6
