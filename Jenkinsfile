pipeline {
    agent {label "sw-wow-thermal_sango-4zh5q"}
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