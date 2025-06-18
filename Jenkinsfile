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
                sh ('newman run /Users/tun/work/ob/test-jenkins/simple-collection.postman_collection.json -e /Users/tun/work/ob/test-jenkins/ob-non-prod.postman_environment.json')
            }
        }
    }
}
