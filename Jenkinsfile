pipeline {
    agent {
        node 'maven'
    }

    stages {
        stage("build") {
            steps {
                sh 'mvn clean deploy'
            }
        }
    }
}
