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
fun main() {

    println("Digite a idade em dias:")
    val totalDias = readLine()!!.toInt()

    val anos = totalDias / 365
    val restoAnos = totalDias % 365

    val meses = restoAnos / 30
    val dias = restoAnos % 30

    println("$anos anos, $meses meses e $dias dias")
}

```

#### Ex 8.
```kotlin
fun main() {

    println("Coloque aqui sua primeira nota")
    var nota1 = readLine()!!.toDouble()
    
    println("Coloque aqui sua segunda nota")
    var nota2 = readLine()!!.toDouble()
    
    println("Coloque aqui sua terceira nota")
    var nota3 = readLine()!!.toDouble()
    
    var media = (nota1 + nota2 + nota3) / 3 
    println("Media: $media")
}
```

#### Ex 9.
```kotlin
fun main() {

    println("Digite o tempo do evento em segundos:")
    val totalSegundos = readLine()!!.toInt()

    val horas = totalSegundos / 3600
    val restoHoras = totalSegundos % 3600

    val minutos = restoHoras / 60
    val segundos = restoHoras % 60

    println("$horas horas, $minutos minutos e $segundos segundos")
}

```

#### Ex 10.
```kotlin
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {
    println("Digite o valor de x1")
    val x1 = readLine()!!.toDouble()
    
    println("Digite o valor para y1")
    val y1 = readLine()!!.toDouble()
    
    println("Digite o valor para x2")
    val x2 = readLine()!!.toDouble()
    
    println("Digite o valor para y2")
    val y2 = readLine()!!.toDouble()
    
    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))
    
    println("A distância entre os pontos é $distancia")
}
```

#### Ex 11.
```kotlin
import kotlin.math.pow

fun main() {
    println("Digite o valor de A (inteiro e positivo):")
    val A = readLine()!!.toInt()
    
    println("Digite o valor de B (inteiro e positivo):")
    val B = readLine()!!.toInt()
    
    println("Digite o valor de C (inteiro e positivo):")
    val C = readLine()!!.toInt()
    
    val R = (A + B).toDouble().pow(2)
    val S = (B + C).toDouble().pow(2)
    
    val D = (R + S) / 2
    
    println("O valor de D é $D")
}
```

#### Ex 12.
```kotlin

```
