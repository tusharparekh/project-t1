pipeline {

    agent {

	docker build - < Dockerfile
    }

    stages {

        stage('Test') {

            steps {

                sh 'cat /etc/motd'

            }

        }

    }

}
