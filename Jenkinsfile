pipeline {
    agent { docker { image 'selenium/hub:latest' , container_name 'selenium-hub' ,
    ports:
      - "4442:4442"
      - "4443:4443"
      - "4444:4444" }
           
    stages {
        stage('build') {
            steps {
                sh 'docker ps'
            }
        }
    }
}
