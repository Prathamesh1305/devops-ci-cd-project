pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/your-username/devops-ci-cd-project.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t yourdockerhub/devops-project:latest .'
            }
        }

        stage('Push Image') {
            steps {
                sh 'docker push yourdockerhub/devops-project:latest'
            }
        }

        stage('Deploy on EC2') {
            steps {
                sh 'ssh ec2-user@your-ec2-ip docker run -d -p 80:80 yourdockerhub/devops-project:latest'
            }
        }
    }
}
