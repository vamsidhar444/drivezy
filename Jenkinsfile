node
{
stage ('checkout')
{
    checkout ([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'github', url: 'https://github.com/vamsidhar444/drivezy.git']]])
     workspace =pwd    
}
stage ('static code analaysis')
{
    echo "static code analaysis"
    
}
stage ('Build')
{
    echo "Bild the code"
}
stage ('unit testing')
{
    echo "unit testing"
}
stage ('delivery')
{
    echo "deliver the code"
}
}

