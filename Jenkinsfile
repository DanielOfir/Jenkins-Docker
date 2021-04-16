pipeline {
    agent {
        docker{
            image 'danielofir/python3.8'
        }

    }

    stages {

        stage('Checking'){
            sh 'pip3 list'
        }

    }

}