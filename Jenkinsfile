pipeline {
    agent {label "thermal_sango"}
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