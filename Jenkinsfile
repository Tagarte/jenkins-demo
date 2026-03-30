pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build en cours...'

            }
        }

        stage('Test') {
            steps {
                echo 'Tests en cours...'

            }
        }

        stage('Execution Script') {
            steps {
                echo 'Exécution du script test.bat...'
                bat 'test.bat'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Déploiement simulé...'

            }
        }
    }

    post {
        success {
            echo 'Pipeline terminé avec succès !'
        }
        failure {
            echo 'Le pipeline a échoué.'
        }
    }
}