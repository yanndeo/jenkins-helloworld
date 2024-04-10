node {
    stage('clone') {
        git 'https://github.com/yanndeo/jenkins-helloworld.git'
    }
     stage('build') {
        sh 'javac Main.java'
    }
     stage('run') {
        sh 'java Main'
    }
}
