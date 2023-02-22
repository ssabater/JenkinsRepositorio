pipeline {
   agent any

   stages {
      stage('Calculo') {
         steps {
            script {
               def numero1 = 2
               def numero2 = 2
               def multiplicacion = numero1 * numero2
               def potencia = numero1 * numero2 + numero1
               println multiplicacion
               println potencia
               writeFile file: 'resultado.txt', text: "La multiplicacion de ${numero1} y ${numero2} es: ${multiplicacion}\nLa potencia de ${numero1} elevado a ${numero2} es: ${potencia}"

               
            }
         }
      }
   }
}
