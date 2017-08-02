#!groovy
node {
    stage('Checkout'){
        checkout scm
    }

    stage('run bazel') {
        sh 'ls -lrta'

        dir('examples/java') {
            sh 'ls -lrta'
            sh 'java -version'
            sh 'bazel build'
        }
    }
}


