pipeline {
    agent { label 'maven'  // Specify the agent label for the pipeline
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