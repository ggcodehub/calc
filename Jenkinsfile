pipeline {
    agent any

    tools {
        maven 'MAVEN_HOME'
    }

    stages {

        stage('Welcome Stage') {
            steps {
                echo 'Welcome to Pipeline'
            }
        }

        stage('Clean Stage') {
            steps {
                sh 'mvn clean'
            }
        }

		stage('Install Maven Project') {
            steps {
                sh 'mvn install'
            }
        }

    }