pipeline {
    agent any
    stages {
        stage('build') {
            steps {
			    sh 'npm --version'
                sh 'echo "hello 2"'
				sh 'pwd'
				sh 'sudo scp -i /opt/key1 -o StrictHostKeyChecking=no -r * ubuntu@54.89.195.179:/tmp'
				sh 'sudo ssh -i /opt/key1 -o StrictHostKeyChecking=no ubuntu@54.89.195.179'
				sh 'sudo mkdir /tmp/tr1'
		     }
        }
    }
}