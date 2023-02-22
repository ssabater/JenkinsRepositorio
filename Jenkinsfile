pipeline
{
    agent any
    stages
    {
        stage ("Creacion de Archivo")
        {
            steps
            {
                script
                {
                    def numero1 = 2
                    def numero2 = 2
                    println numero1
                    println numero2
                    println numero1 * numero2
                    println numero1 + numero2 + numero1 * numero2
                    def info = "calculo" + " " + numero1 * numero2 + " " + numero1
                    writeFile(file: "salida.txt", text:info)
                }
            }
        }
    }
}
