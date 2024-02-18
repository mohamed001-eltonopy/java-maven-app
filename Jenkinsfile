#!/usr/bin/env groovy

pipeline {
    agent none
    stages {
        stage('build') {
            steps {
                script {
                    echo "Building the application from bug fix branch ..."
                }
            }
        }
        stage('test') {
            steps {
                script {
                    echo "Testing the application from bug fix branch ......"
                }
            }
        }
        stage('deploy') {
            steps {
                script {
                    echo "Deploying the application from bug fix branch ......"
                }
            }
        }
    }
}
