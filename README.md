# Atividade2

#### Ex 1.
```kotlin
fun main() {

    val numero1 = readLine()!!.toDouble()
    val numero2 = readLine()!!.toDouble()
    val diferenca = numero1 - numero2

    println(diferenca)
}

```

#### Ex 2.
```kotlin
fun main() {

    println("Digite aqui seu nome")
    val nome = readLine() 

    println("Digite aqui seu sobrenome")
    val sobrenome = readLine() 

    println("$nome $sobrenome!")
}
```

#### Ex 3.
```kotlin
fun main() {

    println("Digite o primeiro número:")
    val num1 = readLine()!!.toDouble()

    println("Digite o segundo número:")
    val num2 = readLine()!!.toDouble()

    val soma = num1 + num2
    val subtracao = num1 - num2
    val multiplicacao = num1 * num2
    val divisao = num1 / num2

    println("Soma: $soma")
    println("Subtração: $subtracao")
    println("Multiplicação: $multiplicacao")
    println("Divisão: $divisao")
}

```

### Ex 4.
```kotlin
fun main() {
    
    println("Digite o valor do lado")
    var lado1 = readLine()!!.toDouble()
    
    println("Digite o valor do lado")
    var lado2 = readLine()!!.toDouble()
    
    var area = lado1 * lado2
    
    println("area: $area")
}
```

#### Ex 5.
```kotlin
fun main() {
    
    println("Digite o valor da base do triângulo")
    var base = readLine()!!.toDouble()
    
    println("Digite o valor da altura")
    var altura = readLine()!!.toDouble()
    
    var area = (base * altura) / 2
    println("area : $area")
}
```

#### Ex 6.
```kotlin
fun main() {
    print("Digite o peso: ")
    val peso = readln().toDouble()

    print("Digite a altura: ")
    val altura = readln().toDouble()

    val imc = peso / (altura * altura)

    if (imc < 18.5) {
        print("Abaixo do peso")
    } else if (imc < 24.9) {
        print("Peso normal")
    } else if (imc < 29.9) {
        print("Sobrepeso")
    } else {
        print("Obesidade")
    }
}
```

#### Ex 7.
```kotlin

```
