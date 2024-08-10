def gv

pipeline {
    agent any
    parameters {
        choice(name: 'VERSION', choices: ['1.1.0', '1.2.0', '1.3.0'], description: '')
        booleanParam(name: 'executeTests', defaultValue: true, description: '')
    }
    stages {
        stage("init") {
            steps {
                echo 'initilizing the jenkins pipeline'
                echo 'after setting polling in Jenkins'
            }
        }
        stage("build") {
            steps {
                echo 'building the application'
            }
        }
        stage("test") {
            steps {
                echo 'testing the application'
            }
        }
        stage("deploy") {
            steps {
                    echo 'deploying the application'
            }
        }
    }   
}
