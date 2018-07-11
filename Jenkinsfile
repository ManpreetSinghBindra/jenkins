pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh "echo 'shell scripts to build project...' > text.txt" 
            }
        }
    }
}    
