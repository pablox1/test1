pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'


		def username = 'Jenkins'
		echo 'Hello Mr. ${username}'
		echo "I said, Hello Mr. ${username}"

            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
