pipeline {
    agent {
        node {
            label 'maven'
        }
    }
stages {
        stage('clone the code') {
            steps {
                git branch: 'master', url: 'https://github.com/rajeshX0057/jenkin-repo.git'
            }
        }
    }
}
