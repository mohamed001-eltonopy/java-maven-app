#!/usr/bin/env groovy
@Library('shared-library') _

pipeline {
    agent none
    stages {
        stage('build') {
            steps {
                script {
                    buildJar()
                }
            }
        }
        stage('test') {
            steps {
                script {
                    echo "Testing the application ....."
                }
            }
        }
        stage('deploy') {
            steps {
                script {
                    echo "Deploying the application ....."
                }
            }
        }
    }
}
