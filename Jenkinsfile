pipeline {
    agent { docker { image 'ubuntu' } }
    stages {
        stage('build') {
            steps {
                sh 'apt-get install cowsay'
				sh 'apt-get install fortune'
				sh 'cowsay | fortune'
            }
        }
    }
}