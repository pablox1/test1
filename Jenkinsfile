pipeline {
    agent any
		def username = 'Jenkins'
		echo 'Hello Mr. ${username}'
		echo "I said, Hello Mr. ${username}"

    stages {
        stage('Build') {
            steps {
                echo 'Building..'



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
