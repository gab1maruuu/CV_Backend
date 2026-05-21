pipeline {
    agent any
    stages {
        stage('Desplegar CV') {
            steps {
                // Asegura los permisos e inyecta el archivo en la ruta de Apache/Caddy
                sh 'mkdir -p /var/www/html/cv_site'
                sh 'cp index.php /var/www/html/cv_site/'
                echo '¡CV desplegado correctamente!'
            }
        }
    }
}
