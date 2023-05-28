pipeline {
 agent any

 stages {
 stage('Checkout') {
 steps {
 // Clonar el repositorio
 git 'https://github.com/LauraRojasss/proyecto-compufix'
 }
 }

 stage('Install Dependencies') {
 steps {
 // Instalar dependencias con npm
     
     sh 'npm install'
 }
 }

 stage('Run Tests') {
 steps {
 // Ejecutar pruebas con npm test
 sh 'npm test'
 }
 }

 stage('Build') {
 steps {
 // Construir la aplicación con npm run build
 sh 'npm run build'
 }
 }


 }
}
