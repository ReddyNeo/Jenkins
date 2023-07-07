pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World neo test branch'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
