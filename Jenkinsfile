pipeline
{
agent any
stages
{
stage('clone')
{
steps
{
 git'https://github.com/snigdha-22/demo3-rep.git'
}
}
stage('build')
{
steps
{
sh 'javac hello.java'
}
}
stage('run')
{
steps
{
sh 'java hello'
}
}
}
}
