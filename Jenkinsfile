pipeline {

    agent any

    stages {
        stage("build") {
            steps {
                echo 'building the applicatoin.................................................................'
                echo "${GIT_URL}"
            }
        }
        stage("test") {
            steps {
                echo 'testing the applicatoin...'
            }
        }
        stage("deploy") {
            steps {
                echo 'deploying the applicatoin...'
            }
        }
    }
}