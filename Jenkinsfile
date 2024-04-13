pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Hello') {
            steps {
                git branch: 'master', url: 'https://github.com/rajeshX0057/jenkin-repo.git'
            }
        }
    }
}
