node {
    stage('Java clone') {
        git 'https://github.com/shashikantsa/java.git'
    }
    stage('Build java') {
        sh '''javac Test.java
              java Test'''
    }
