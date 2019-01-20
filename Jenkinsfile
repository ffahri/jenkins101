pipeline {
    agent { docker { image 'node:7-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version
		sh 'echo "Hello"'
            }
        }
    }
    post{
       always {
	echo 'Jenkins !!!'}
	success { echo 'success'}
}
}
