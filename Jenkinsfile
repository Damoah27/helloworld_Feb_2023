pipeline {
    agent any
    stages {
        stage (''Build Step) {
            steps {
                echo 'Build Step'
                sleep 10
               
                }
             }
             stage('Test') {
                 steps {
                     echo'Test Step'
                 }
             }
             stage('Deploy') {
                 steps {
                     echo 'Deploy Step'
                     sleep 10
                 }
             }
             stage('Docker') {
                 steps {
                     echo 'Image Step'
                 }
              }
          }
}
