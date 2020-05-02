pipeline {
    agent {
        docker {
            image 'maven' 
            args '-v C:/Users/dareddy/.m2'
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
