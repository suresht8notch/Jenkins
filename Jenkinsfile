pipeline {
    agent any
    parameters {
      choice(choices: 'dev\ntest\nstage\nwhat-if\nprod\nbatch', description: 'Select the target environment.', name: 'ENVIRONMENT')
      gitParameter(defaultValue: 'origin/main', description: 'Branch/tag to build and deploy', name: 'BRANCH_TAG', type: 'PT_BRANCH_TAG')
    }
    stages {
        stage('Git Checkout') {
            steps {
                echo 'Git checkout and ran the Jenkins file!'
            } 
        }
    }
} 
