pipeline {
    agent any 
    stages {
        stage('Prepare') {
            steps {
                echo "preparing..."
            }
        }
        stage('run newman') {
            steps {
                newman run /Users/tun/work/ob/test-jenkins/simple-collection.postman_collection.json
            }
        }
    }
}
