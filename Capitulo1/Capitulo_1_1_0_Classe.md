# Classe

Uma classe é o principal bloco de construção de um programa. Todo código em um programa deve estar contido em pelo menos uma classe.

## Exemplo

Abaixo vemos uma classe chamada `HelloWorld`.

```java
public class HelloWorld {
    public static void main(final String args[]) {
        System.out.println("Hello world!");
    }
}
```
**Código 1** - Hello World em Java

Há muito o que podemos falar sobre esse código. Por enquanto, é necessário apenas conseguir separá-lo em duas partes:

- Declaração
- Corpo

Vamos identificar essas partes no código acima.

#### Declaração

É onde definimos o nome da classe, por exemplo.

```java
public class HelloWorld
```
**Código 2** - Declaração da classe `HelloWorld`.

> :bulb: Um trecho de código não compila corretamente.

Falaremos mais sobre esse código adiante.

#### Corpo

O corpo de uma classe é igualmente importante, pois contém o que ela faz, por exemplo.

```java
{
    public static void main(final String args[]) {
        System.out.println("Hello world!");
    }
}
```
**Código 3** - Corpo da classe `HelloWorld`.

> :bulb: Um trecho de código não compila corretamente.

Esse corpo de classe contém um código que imprime o texto "*Hello world!*" no terminal.

O corpo de uma classe é delimitado pelos caracteres `{}`.

## FAQ

#### Uma classe pode não ter corpo?

O corpo pode estar vazio, `{}`, mas ele sempre deve estar presente.

#### Como criar uma classe chamada `Person`?

```java
public class Person {}
```

> :bulb: Note que essa classe possui um corpo vazio.

#### Como criar uma classe chamada `PaymentMethod`?

```java
public class PaymentMethod {}
```

#### Toda classe possui o modificador de acesso `public`?

Geralmente sim, mas existem outros modificadores que também podem ser usados.
