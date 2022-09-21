pipeline {
    agent any
    stages{
    stage("build"){
        steps{
            sh 'docker build -t apachepage:2 .'
            sh 'docker history apachepage:2'
        }
    }
    }
}
