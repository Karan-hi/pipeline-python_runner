pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'sudo python3 --version'
            }
        }
        stage('Compile') {
			steps {
				sh 'sudo python3 add2nums.py'
			}
		}
		stage('Test') {
			steps {
				sh 'sudo python3 test.py'
			}
		}
    }
}
