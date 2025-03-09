pipeline {
    agent any
    parallel{
        stages {

            stage('Example') {
                steps {
                    echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
                }
            }
            stage('Build') {
                steps {
                    echo 'Building..'
                }
            }
            stage('Test') {
                steps {
                    echo 'Testing..'
                }
            }
            stage('Deploy') {
                steps {
                    echo 'Deploying....'
                }
            }
        }
    }
}


////Previous
//pipeline {
//    agent any
//
//    stages {
//        stage('Example') {
//            steps {
//                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
//            }
//        }
//        stage('Build') {
//            steps {
//                echo 'Building..'
//            }
//        }
//        stage('Test') {
//            steps {
//                echo 'Testing..'
//            }
//        }
//        stage('Deploy') {
//            steps {
//                echo 'Deploying....'
//            }
//        }
//    }
//}
