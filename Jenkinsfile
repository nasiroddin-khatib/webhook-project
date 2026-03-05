pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/nasiroddin-khatib/webhook-project'
            }
        }
	

	stage('build') {
	    steps {
		sh 'mvn clean package'
	  }
	}
        
   }
}

