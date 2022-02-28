pipeline {

    agent { dockerfile true }
        stages {
            stages('Test') {
            steps {
                sh '''
                    ruby -v
                '''
            }
        }   
   }
   
}