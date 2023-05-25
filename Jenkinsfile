pipeline {
    agent any
    stages {
        stage('hello-world-jenkinsfile') {
            steps {
                echo 'Hello from jenkinsfile'
                echo "Build number is ${currentBuild.number}"
            }
        }
    }
}