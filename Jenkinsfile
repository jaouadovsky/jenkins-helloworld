node {
    stage('Clone') {
    git branch: 'main', url: 'https://github.com/jaouadovsky/jenkins-helloworld.git'
    }
    stage('Build') {

    sh label: '', script: '''
        javac Main.java
        '''
    }
    stage('Run') {
    sh label: '', script: '''
        java Main
        '''
    }
}
