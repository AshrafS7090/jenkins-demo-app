pipeline {

agent any

stages {

stage('Checkout') {
steps {
git 'https://github.com/yourusername/jenkins-demo-app.git'
}
}

stage('Build') {
steps {
sh 'echo Building application'
}
}

stage('Deploy') {
steps {
sh 'echo Deploying application'
}
}

}

}
