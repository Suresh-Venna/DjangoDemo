pipeline{
    agent none
    stages{
        stage('build'){
            // agent{
            //     docker {
            //         image 'spython:2-alpine'
            //     }
            // }
            steps{
                // sh 'python manage.py runserver'
                echo 'build done'
            }
        }
        stage('test'){
            // agent{
            //     docker {
            //         image 'spython:2-alpine'
            //     }
            // }
            steps{
                echo "test done"
            }
        }
        stage('deploy'){
            // agent{
            //     docker {
            //         image 'spython:2-alpine'
            //     }
            // }
            steps{
                echo "deploy  done"
            }
        }
    }
}
