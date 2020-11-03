pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                script {
		   echo 'do dev stuff'
			try {
			echo 'run tests'
			} catch {
			echo 'abort'
			}
			echo 'git checkout test';
			echo 'git merge dev';
                    }
                }
            }
        }

        stage('test') {
            steps {
                script {
                    echo 'do test stuff'
		    git 'merge 

			
                }
            }
        }

        stage('stage') {
            steps {
		echo 'Do stage stuff'
            }
        }

	stage('prod') {
            steps {
                echo 'Do prod stuff'
           }
        }
    }
}
