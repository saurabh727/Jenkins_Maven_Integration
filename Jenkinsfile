pipeline{
agent any
stages {
  stage('Source') {
    steps {
      // One or more steps need to be included within the steps block.
    }

    tools {
      git 'https://github.com/saurabh727/Jenkins_Maven_Integration.git'
    }
  }

}
stage('Compile') {
  tools {
    maven 'Maven-3.6.3'
  }
  steps {
    mvn package
  }
}
}
