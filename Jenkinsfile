#!groovy
node {
    stage('Checkout'){
        checkout scm
    }

    stage('run bazel') {
        sh 'ls -lrta'

        dir('examples/java') {
            sh 'bazel build'
        }
    }
}


