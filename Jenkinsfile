#Jenkins DSL is Grovvy
# pipeline --> stages --> stage --> steps --> scripts
pipeline {

    stages {
        stage('Code Compilation') {
            steps {
                echo 'code compilation is starting'
                sh 'mvn clean compile'
				echo 'code compilation is completed'
            }
        }
        stage('Code Package') {
            steps {
                echo 'code packing is starting'
                sh 'mvn clean package'
				echo 'code packing is completed'
            }
        }
        stage('Create Docker Image') {
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
        stage('Docker Image Tag') {
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
        stage('Push Docker Image to Docker HUB') {
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
        stage('Push Docker Image to AWS ECR') {
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
        stage('Push Docker Image to Nexus') {
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
        stage('Deploy APP to K8s CLuster') {
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
    }
}