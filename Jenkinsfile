pipeline {
    agent any
    stages {
        stage ("Build") {
            steps {
                sh 'docker build -t muddanadevops/abinay:bank .'
            }
        }
        stage ("Deploy") {
            steps {
                sh 'docker run -itd --name bank2 -p 9999:80 muddanadevops/abinay:bank'
            }
        }
    }
}
