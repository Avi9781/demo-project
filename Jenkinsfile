pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'welcome to build'
            }
        }
        stage('test') {
            steps {
                echo 'welcome to test'
            }
        }
         stage('deploy') {
            steps {
                git branch: 'main', url: 'https://github.com/Avi9781/demo-project.git'
            }
        }
        
    }
}

