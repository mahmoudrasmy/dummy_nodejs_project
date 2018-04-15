pipeline {
    agent any
    stages {
        stage('build') {
            steps {
			    sh 'npm --version'
                sh 'echo "hello"'
				sh 'pwd'
				sh 'sudo scp -i /opt/key -o StrictHostKeyChecking=no -r * ubuntu@54.89.195.179:/opt/to_deploy'
		     }
        }
    }
}