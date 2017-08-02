#!groovy
node {
    stage('run bazel') {
        dir('examples/java/build') {
            sh 'bazel build'
        }
    }
}


