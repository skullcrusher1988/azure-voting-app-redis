pipeline {
    agent any

    stages {
        stage('verify branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage(){
           steps{
              sh(script: 'docker image -a')
              
           }
        }

    }
}
