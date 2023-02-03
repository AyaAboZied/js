pipeline {
    aagent { label 'jenkins-ubuntu-slave' }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('build') {
            steps {
                echo 'building'
                sh "ls"
            }
        }
    }
}

