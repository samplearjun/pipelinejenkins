node (label: 'slave'){
    
   stage('Build') {
        docker.image('maven:3.9.0-eclipse-temurin-11').inside {
            sh 'mvn --version'
        }
    }
}
