pipeline {
    agent any
    stages {
        stage('build') {
            steps {
			    sh 'npm --version'
                sh 'echo "hello 2"'
				sh 'pwd'
				sh 'sudo scp -i /opt/key1 -o StrictHostKeyChecking=no -r * ubuntu@54.89.195.179:/tmp'
				sh 'sudo ssh -i /opt/key1 -o StrictHostKeyChecking=no ubuntu@54.89.195.179 "sudo chmod 777 /tmp/start_server.sh"'
				sh 'sudo ssh -i /opt/key1 -o StrictHostKeyChecking=no ubuntu@54.89.195.179 "sudo /tmp/start_server.sh"'
				sh 'pwd'
		     }
        }
    }
}