pipeline {
    agent {
        node {
            label 'maven'
        }
    }
    environment {
        PATH = "/opt/apache-maven-3.9.6/bin:$PATH"
    }
    stages {
        stage("build") {
            steps {
                echo "#########Build started#####"
                sh 'mvn clean deploy -Dmaven.test.skip=true'
                echo "#########Build completed#####"
            }
        }
    }
}
