# DESELVOLVIMENTO-MOBILE
fun main(){

    val a = 2
    val b = 2

    val resultado = a + b
    println(resultado)

    var usuario = "Daniel Silva"
    var texto = "Boa noite, seja muito bem-vindo, $usuario !!!"
    println(texto)

    val text2 = """
        exemplo de texto
        com mais
        de uma linha
        """
    print(text2)


    -------------------------------------------------------------------------------------------

    fun main(){

    val valor = arrayListOf(2,4,6,8,10).sum()
    val media = valor / 5

    println("A media dos valor é $media")

    if(media <= 5){
        println("media é menor que 5")
    }
    if (media == 5){
        println("media é 5")
    }
    if (media > 5){
        println("media é maior que 5")
    }
    if (media > 100){
        print("meia é muito grande")
    }




}
-----------------------------------------------------------------------------------------------------------


fun imprimir(){

   for (numero in 1..20){
       println("$numero")
    }

}

fun main(){
    imprimir()
}

--------------------------------------------------------------------------------------------------------------------------
