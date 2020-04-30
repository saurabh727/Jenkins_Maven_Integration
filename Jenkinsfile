pipeline{
    agent any
    stages {
        stage("Source") {
            steps {
                git 'https://github.com/saurabh727/Jenkins_Maven_Integration.git'
                  }
                        }
        
        stage("Maven Build") {
            tools {
                maven 'Maven-3.6.3'
  }
                steps {
                    sh "mvn package"
                      }
                  }
                             }
           }
}
