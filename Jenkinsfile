pipeline {
    agent any
    stages {
	stage("Deploy to dev") {
	   steps {
	      sh "ansible-playbook /etc/ansible/playbook/deploy-dev.yml"
	   }
	}
    }
}
