pipeline {
    agent {label "sw-wow-thermal_sango-s1jgc"}
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