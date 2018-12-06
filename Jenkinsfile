pipeline {
    agent { docker { image 'ubuntu' } }
    stages {
        stage('build') {
            steps {
                sh 'sudo apt-get install cowsay'
				sh 'sudo apt-get install fortune'
				sh 'sudo cowsay | fortune'
            }
        }
    }
}