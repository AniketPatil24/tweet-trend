pipeline {
    agent {
        node 'maven'
    }

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/AniketPatil24/tweet-trend.git'
            }
        }
    }
}