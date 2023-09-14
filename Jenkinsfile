pipeline {
    agent any
    parameters {
      choice(choices: 'dev\ntest\nstage\nwhat-if\nprod', description: 'Select the target environment.', name: 'ENVIRONMENT')
    }
    stages {
        stage('Git Checkout') {
            steps {
                echo 'Git checkout and ran the Jenkins file!'
            } 
        }
    }
} 
