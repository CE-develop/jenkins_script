//Previous
pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('Build') {
//            steps {
//                echo 'Building..'
//            }
            parallel {
                stage('Parallel1') {
                    agent any
                    steps {
                        echo "Parallel1_step1"
                    }
                    steps {
                        echo "Parallel1_step2"
                    }
                    steps {
                        echo "Parallel1_step3"
                    }
                }
                stage('Parallel2') {
                    agent any
                    steps {
                        echo "Parallel2_step1"
                    }
                    steps {
                        echo "Parallel2_step2"
                    }
                    steps {
                        echo "Parallel2_step3"
                    }
                }
                stage('Parallel3') {
                    agent any
                    steps {
                        echo "Parallel3_step1"
                    }
                    steps {
                        echo "Parallel3_step2"
                    }
                    steps {
                        echo "Parallel3_step3"
                    }
                }
                stage('Parallel4') {
                    agent any
                    steps {
                        echo "Parallel4_step1"
                    }
                    steps {
                        echo "Parallel4_step2"
                    }
                    steps {
                        echo "Parallel4_step3"
                    }
                }
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
