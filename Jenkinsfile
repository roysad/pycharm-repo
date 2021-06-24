properties([parameters([string(defaultValue: 'Roy', name: 'NAME')]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("one"){
        git branch: 'main', url: 'https://github.com/roysad/pycharm-repo.git'
        sh "cat 1.txt"
    }
    
}
