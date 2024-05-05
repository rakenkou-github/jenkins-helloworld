node {
    stage('Clone') {
        git 'https://github.com/rakenkou-github/jenkins-helloworld.git'
    }

    stage('Build') {
        sh '''
            javac Main.java
        '''
    }

    stage('Clone') {
        sh '''
            java Main
        '''
    }
}