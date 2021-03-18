pipeline {
    agent any
    stages {
	stage("Deploy to product") {
	   sh "ansible-playbook /etc/ansible/playbook/deploy-prod.yml"
	}
    }
}
