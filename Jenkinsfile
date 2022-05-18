pipeline {
    agent {
	node {
	    label 'GRIDENGINE'
	}
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		sleep 5
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		sleep 4
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
		sleep 5
            }
        }
        stage('Parameter') {
            steps {
                echo "$PUBLISH"
                sleep 5
            }
        }
        stage('PWD') {
            steps {
                pwd
		ls -al
		echo "Done"
                sleep 5
            }
        }

    }
}
