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
                sh 'mvn clean package'
            }
        }           
        stage ('deploy') {
            steps {
                echo "This is deploy stage"
            }
        }                    
    }
}
