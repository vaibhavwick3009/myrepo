pipeline {
agent any
stages {
  stage('Checkout') {
    steps {
// Checkout code from the Git repository
     sh 'echo checking out'
   }
  }
  stage ('webhook') {
    steps { 
      sh 'echo hello'
    }
  }  
  stage ('webhook2') {
    steps { 
      sh 'echo hello2'
    }
  }  
stage('Build') {
  steps {
// Build the Java application (replace with your build commands)
  sh 'javac -version'
 }
}
stage('Deploy') {
  steps {
  // Deploy the application (replace with your deployment commands)
   sh 'echo "Deploying the application"'
   }
  }
 }
}
