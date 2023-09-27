pipeline {
    agent any // Ejecutar en cualquier agente disponible

    stages {
        stage('Build') {
            steps {
                script {
                    // Definir dos números para sumar
                    def numero1 = 5
                    def numero2 = 3

                    // Realizar la suma
                    def resultado = numero1 + numero2

                    // Mostrar el resultado en la consola
                    echo "La suma de $numero1 y $numero2 es igual a $resultado"
                }
            }
        }
    }
}
