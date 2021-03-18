pipeline {
    agent any
    stages {
	stage("Deploy to product") {
	   steps {
	      sh "ansible-playbook /etc/ansible/playbook/deploy-prod.yml"
	   }
	}
    }
}
