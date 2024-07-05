pipeline {
    agent any
    stages {
        stage('provision') {
            steps {
                sh ' rm -rf /var/www/html/* '
            }
        }
	stage('deploy'){
	steps{
	sh  "mv * /var/www/html"
   	 }
	}
}
}
