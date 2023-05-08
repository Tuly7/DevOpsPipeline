pipeline {
agent any
stages {
stage('Checkout') {
steps {
checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Tuly7/DevOpsDemo']])
}
}
stage('Test') {
steps {
sh 'echo test'
}
}
stage('Deploy') {
steps {
sh 'echo deploy'
}
}
}
}
