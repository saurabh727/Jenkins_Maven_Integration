pipeline{
    agent any
    
    environment{
        PATH = "C:\Program Files\apache-maven-3.6.3:$PATH"
    }
    stages {
        stage("Source") {
            steps {
                git 'https://github.com/saurabh727/Jenkins_Maven_Integration.git'
                  }
                        }
        
        stage("Maven Build") {
             steps {
                 sh "mvn package"
                   }
                             }
           }
}
