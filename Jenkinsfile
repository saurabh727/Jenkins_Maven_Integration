pipeline{
    agent any
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
