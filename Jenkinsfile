pipeline {
    agent any
    stages {
	stage("Deploy to dev") {
	   sh 'ansible-playbook /etc/ansible/playbook/deploy-dev.yml'
	}
    }
}
