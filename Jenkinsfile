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
    }
}
