#!groovy
node {
    stage('run bazel') {
        sh 'ls -lrta'

        dir('examples/java/build') {
            sh 'bazel build'
        }
    }
}


