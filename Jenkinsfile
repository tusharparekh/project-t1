pipeline {

    agent {

	docker build 
    }

    stages {

        stage('Test') {

            steps {

                sh 'cat /etc/motd'

            }

        }

    }

}
