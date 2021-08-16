properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("close"){
        git branch: 'main', url: 'https://github.com/viktor1298-dev/my-project.git'
    }
    stage("show files"){
        bat "dir"
    }
}
