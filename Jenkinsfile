pipeline {
    agent any

    stages {
        stage('Build Dev') {
            steps {
                echo 'Build Dev..' + env.BRANCH_NAME
                sh '''#!/bin/bash
                      test -f k3s/dev || echo "no dev environment" && exit 0
                      cd k3s/production/ && skaffold run
                   '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..' + env.BRANCH_NAME
            }
        }
        stage('Build Production') {
            steps {
                echo 'Build Production....' + env.BRANCH_NAME
                sh("cd k3s/production/ && skaffold run")
            }
        }
    }
}
