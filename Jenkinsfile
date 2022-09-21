pipeline {
    agent any
    stages{
        stage("checkout"){
            steps{
                sh 'git clone git@github.com:dhanakopparthi/new.git'
            }
        }
    stage("build"){
        steps{
            sh 'docker build -t apachepage:2 .'
            sh 'docker history apachepage:2'
        }
    }
    }
}
