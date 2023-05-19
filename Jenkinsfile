node {
    docker.image('maven').inside('-p 8000:8000') {
        stage('Build') {
                sh 'mvn clean package'
            }
        stage('Test') { 
                sh 'mvn test' 
        }
    }
}