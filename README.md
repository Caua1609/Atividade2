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
fun main() {
    print("Digite o custo de fábrica do carro: ")
    val custoFabrica = readLine()!!.toDouble()

    val percentualDistribuidor = 0.28
    val percentualImpostos = 0.45

    val custoConsumidor = custoFabrica * (1 + percentualDistribuidor + percentualImpostos)

    println("O custo ao consumidor é: R$ %.2f".format(custoConsumidor))

```

#### Ex 13.
```kotlin
fun main() {
    print("Digite o valor de a: ")
    val a = readLine()!!.toDouble()
    print("Digite o valor de b: ")
    val b = readLine()!!.toDouble()
    print("Digite o valor de c: ")
    val c = readLine()!!.toDouble()
    print("Digite o valor de d: ")
    val d = readLine()!!.toDouble()
    print("Digite o valor de e: ")
    val e = readLine()!!.toDouble()
    print("Digite o valor de f: ")
    val f = readLine()!!.toDouble()

    val denominador = a * e - b * d

    if (denominador == 0.0) {
        println("O sistema não tem solução única.")
    } else {
        val x = (c * e - b * f) / denominador
        val y = (a * f - c * d) / denominador

        println("Valor de x = $x")
        println("Valor de y = $y")
    }
}

```

#### Ex 14.
```kotlin
fun main() {
    
    println("informe seu salario atual")
    var salarioAtual = readLine()!!.toDouble()
    
    var salarioNovo = salarioAtual * 1.25
    
    println("novo salario: $salarioNovo")
}

```

#### Ex 15.
```kotlin
fun main() {
    println("Informe o salário atual do funcionário:")
    val salarioAtual = readLine()!!.toDouble()

    println("Informe o percentual de aumento (%):")
    val percentualAumento = readLine()!!.toDouble()

    val salarioNovo = salarioAtual * (1 + percentualAumento / 100)

    println("Novo salário: $salarioNovo")
}

```

#### Ex 16.
```kotlin
fun main() {
    println("Digite seu ano de nascimento:")
    val anoNascimento = readLine()!!.toInt()

    println("Digite o ano atual:")
    val anoAtual = readLine()!!.toInt()

    val idadeAnos = anoAtual - anoNascimento
    val idadeMeses = idadeAnos * 12
    val idadeSemanas = idadeAnos * 52
    val idadeDias = idadeAnos * 365 

    println("Idade da pessoa em anos: $idadeAnos")
    println("Idade da pessoa em meses: $idadeMeses")
    println("Idade da pessoa em semanas: $idadeSemanas")
    println("Idade da pessoa em dias (aproximado): $idadeDias")
}

```

#### Ex 17.
```kotlin
   
fun main() {
    println("Digite o peso do saco de ração (em kg):")
    val pesoSacoKg = readLine()!!.toDouble()

    println("Digite a quantidade de ração diária para cada gato (em gramas):")
    val racaoPorGato = readLine()!!.toDouble()

    val numeroGatos = 2
    val dias = 5

    val pesoSacoGramas = pesoSacoKg * 1000

    val consumoTotal = racaoPorGato * numeroGatos * dias

    val restante = pesoSacoGramas - consumoTotal

    println("Ração restante após $dias dias: $restante gramas")
}

```

#### Ex 18.
```kotlin
fun main() {
    println("Digite o valor da variavel A")
    var variavelA = readLine()!!.toDouble()
    
    println("Digite o valor da variavel B")
    var variavelB = readLine()!!.toDouble()
    
    println("Antes da troca: a = $variavelA, b = $variavelB")
     
    val temp = variavelA
    variavelA = variavelB
    variavelB = temp
    
    println("Depois da troca: a = $variavelA, b = $variavelB")
}

```

#### Ex 19.
```kotlin
fun main() {
    println("Digite o valor do comprimento")
    var comprimento = readLine()!!.toDouble()
    
    println("Digite o valor da altura")
    var altura = readLine()!!.toDouble()
    
    println("Digite o valor da largura")
    var largura = readLine()!!.toDouble()
    
    var volume = comprimento * altura * largura
    println("volume: $volume")
    
}

```
