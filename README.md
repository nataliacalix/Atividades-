```kotlin
fun main() {
    val peso = 50.0
    val altura = 1.64

    val imc = peso / (altura * altura)

    println("Peso: " + peso)
    println("Altura: " + altura)
    println("IMC: " + imc)

    if (imc < 18.5) {
        println("Abaixo do peso")
    } else if (imc < 25) {
        println("Peso normal")
    } else if (imc < 30) {
        println("Sobrepeso")
    } else {
        println("Obesidade")
    }
}
