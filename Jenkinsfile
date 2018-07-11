pipeline {
    stages {
            agent { docker { image 'maven:3.3.3' } }

       stage('build') {
            steps {
                sh "echo 'shell scripts to build project...' > text.txt" 
            }
        }
    }
}    
