@Library('pipeline-library') _

node {
    stage("Show Files") {
        checkout scm
        sh 'ls'
        myTest{
            hello = 'hello'
        }
        sh 'echo "Hello!!"'
    }
}
