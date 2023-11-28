pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Étapes de construction, par exemple, utiliser Maven pour construire un projet Java
                sh 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                // Étapes de test, par exemple, exécuter des tests unitaires
                sh 'mvn test'
            }
        }

        stage('Deploy') {
            steps {
                // Étapes de déploiement, par exemple, déployer sur un serveur
                sh 'deploy-script.sh'
            }
        }
    }
}
