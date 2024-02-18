#!/usr/bin/env groovy
@Library('shared-library@new-feature') _

pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                script {
                    buildJar(name: "finance",dayOfWeek: "tues")
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
