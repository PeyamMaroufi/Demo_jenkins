pipeline {
    agent {label "Built-In Node"}
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