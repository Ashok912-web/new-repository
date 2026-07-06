pipeline{
    agent{
        label "java-slave"
    }
    stages{
        stage('Maven'){
            steps {
                echo "Hello,Welocome to maven sectiom"
                sh : "mvn --version"
            }
        }
    }
}
