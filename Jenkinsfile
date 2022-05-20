pipeline {
    agent any

    stages {
        stage('BUILD') {
            steps {
		    echo 'BUILD New World'
		    
            }
        }
	stage('TEST') {
		steps {
			echo 'TEST New World'
		}
	}
	
	stage('QA') {
		steps {
			echo 'QA New World'
		}
        }
	stage('PROD-2') {
		steps {
			echo 'PROD-2 New World'
                }
        }
	stage('PROD') {
		steps {
			echo 'PROD New World'
		}
        }
	post
	    {
		    always
		    {
			    emailext body: 'Good Work.', subject: 'Details Regarding current Jenkins Job', to: 'vaibhavtomar082@gmail.com'
		    }
  	    }
	
    }
}
