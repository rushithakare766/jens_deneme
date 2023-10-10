pipeline {
    agent any

    stages {
        stage('Fetch File') {
            steps {
                // Use 'checkout' to fetch the entire repository
                checkout scm
                
                // Copy the specific file to the workspace
                sh "cp app.py /home/rushikesh/.jenkins/workspace/"
            }
        }
    }
}
