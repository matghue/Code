pipeline {
agent any
stages {
stage("build") {
steps {
echo 'Building the application'
}
}
stage("test") {
steps {
echo 'Testing the application'
}
}
stage("deploy") {
steps {
echo 'Deploying the application'
}
}
}
}

pipeline {
agent any
tools {
maven 'Maven'
}
stages {
stage("build") {
steps {
sh 'mvn -v'
}
}
stage("test") {
steps {
echo 'Running tests'
}
}
stage("deploy") {
steps {
echo 'Deploying application'
}
}
}
}