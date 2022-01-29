pipeline{
    agent any
    stages
    { stage('Build'){
        steps{
            echo 'Hello World '
            sh '/root/apache-maven-3.6.3/bin/mvn clean package'
        }
    }
    }
    
}
