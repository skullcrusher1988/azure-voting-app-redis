pipeline {
    agent any

    stages {
        stage('verify branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage(('doirrrt'){
           steps{
              pwsh(script: 'docker image -a')

           }
        }

    }
}
