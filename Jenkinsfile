pipeline {
    agent any 
    stages {
        stage('Build ServiceOne') {
            steps {
                echo 'Built The Source Of ServiceOne!' 
            }
        }
       stage('Deploy ServiceOne') {
          steps {
              echo 'Deployed The Successful Build Of ServiceOne!' 
          }
       }
        stage('Test ServiceOne') {
          steps {
              echo 'Completed The Testing Of The ServiceOne!' 
          }
       }
       stage('Deploy Build Output Of ServiceOne To Artifactry') {
          steps {
              echo 'Deployed The Successful Build Output Of ServiceOne To Artifactry!' 
          }
       }
    }
}
