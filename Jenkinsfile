pipeline {
    agent {
        docker{
            image 'danielofir/python3.8'
        }
    }

    stages {

        stage('Checkout SCM'){
            steps{
            checkout scm
            }
        }

        stage('Checking'){
            steps{
                sh 'pip3 list'
            }
        }

    }

        // stage('Checkout SCM'){
        //     checkout scm
        // }


        // stage('Checking'){
        //     sh 'pip3 list'
        // }

}