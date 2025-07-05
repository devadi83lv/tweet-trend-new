pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone Repository') {
            steps {
                script {
                    // Clone the repository using the provided URL and branch
                    git branch: 'main', url: 'https://github.com/devadi83lv/tweet-trend-new.git'
            }
        }
    }
}
}