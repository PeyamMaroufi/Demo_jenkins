pipeline {
    agent {label "built-in"}
    options {
        buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5' )
        disableConcurrentBuilds()
    }
    stages {
        stage('Hello'){
            steps {
                echo "hello"
            }
        }
    }
}