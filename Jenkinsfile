pipeline {
    agent any
     stage('Installation de Maven') {
                steps {
                    echo "Maven est installé"
                }
            }
    stages {
        stage('Phase de build ') {
            steps {
                echo "Le projet est buildé"
            }
        }
        stage('Phase de test') {
            steps {
                echo "Les tests sont lancés"
            }
        }
        
        stage('Phase de test d\'intégration') {
            steps {
                echo "Les tests d'intégration sont lancés"
            }
        }
        
        stage('Verification de la qualité') {
            steps {
                echo "La qualité est vérifiée"
            }
        }
        
        stage('Phase de déploiement') {
            steps {
                echo "Le projet est déployé"
            }
        }

    }
}
