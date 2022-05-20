pipeline {
    agent any
     
    stages {
        stage('BUILD') {
            steps {
                echo "Ok"
            }
        }
    }
    post {
        always {
	    emailext body: 'Good Work.', subject: 'Details Regarding current Jenkins Job', to: 'vaibhavtomar082@gmail.com'
            }
    }
}


