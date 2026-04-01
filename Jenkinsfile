node {
    stage('git clone') {
        git branch: 'main', url: 'https://github.com/Eswar-2577/spring-petclinic.git'
    }
    stage('package') {
       sh 'mvn package'
    }
}
