pipeline {
    agent any
    stages {
        stage ('cloning') {
            steps {
                git branch: 'main', url: 'https://github.com/Garv173/java-onlinebookstore.git'
            }
        }
        stage ('build') {
            steps {
                echo "This is build stage"
            }
        }
        stage ('sonarscan') {
            steps {
                echo "This is sonarscan stage"
            }
        }               
        stage ('push') {
            steps {
                echo "This is push stage"
            }
        }
        stage ('deploy') {
            steps {
                echo "This is deploy stage"
            }
        }                    
    }
}
