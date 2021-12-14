pipeline {
	agent any
	tools {
	    nodejs "Node v16.2.0"
	}
	stages {
		stage("Build") {
			steps {
				script {
				    echo "Building jenkinstest project..."
            bat "npm -v"
            bat "npm run build"
				}
			}
		}
  }
}
