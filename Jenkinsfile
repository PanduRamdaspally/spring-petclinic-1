node {
    stage('scm'){
        git 'https://github.com/zensoftllc/spring-petclinic.git'
    }
    stage('build'){
        sh 'mvn package'
    }
}