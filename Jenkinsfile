pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Build the java code'
                git 'https://github.com/arul24ar/HelloJenkins'
                sh label: '', script: '''javac hello.java
                java hello'''
            }
        }
    }
}
