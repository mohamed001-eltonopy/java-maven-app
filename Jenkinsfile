#!/usr/bin/env groovy

@Library('shared-library') _
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                script {
                   buildJar(name: "finance",version: "jmv")
                }
            }
        }
        stage('test') {
            steps {
                script {
                    echo "Testing the application..."
                }
            }
        }
        stage('deploy') {
            steps {
                script {
                    echo "Deploying the application..."
                }
            }
        }
    }
}
