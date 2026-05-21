pipeline {
    agent any
    stages {
        stage('Desplegar CV') {
            steps {
                // Despliegue en el directorio interno del espacio de trabajo público de Jenkins
                sh 'mkdir -p ./deploy_site'
                sh 'cp index.php ./deploy_site/'
                echo '¡CV desplegado en el entorno local de Jenkins con éxito!'
            }
        }
    }
}
