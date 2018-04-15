pipeline {
    agent any
    stages {
        stage('build') {
            steps {
			    sh 'npm --version'
                sh 'echo "hello"'
				sh 'pwd'
				sh 'scp -i /opt/key -r * ubuntu@54.89.195.179:/opt/to_deploy'
		     }
        }
    }
}