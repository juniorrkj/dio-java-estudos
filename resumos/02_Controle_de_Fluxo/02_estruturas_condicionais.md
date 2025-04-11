# 🔀 Estruturas Condicionais em Java

As **estruturas condicionais** permitem que um programa tome decisões com base em condições lógicas. São usadas para executar blocos diferentes de código dependendo dos valores avaliados.

---

## 📌 Sintaxe do `if`, `else if` e `else`

```java
if (condicao) {
    // executa se condicao for verdadeira
} else if (outraCondicao) {
    // executa se a outraCondicao for verdadeira
} else {
    // executa se nenhuma das anteriores for verdadeira
}
```

---

## ✅ Exemplo prático com `if`

```java
int idade = 18;

if (idade >= 18) {
    System.out.println("Maior de idade");
} else {
    System.out.println("Menor de idade");
}
```

---

## 🎛️ Estrutura `switch`

Usado para testar igualdade em múltiplos valores possíveis.

```java
int dia = 3;

switch (dia) {
    case 1:
        System.out.println("Domingo");
        break;
    case 2:
        System.out.println("Segunda");
        break;
    case 3:
        System.out.println("Terça");
        break;
    default:
        System.out.println("Dia inválido");
}
```

---

## ✅ Dicas

- Sempre use `break` após cada `case` (evita execução em cascata).
- `default` é opcional, mas recomendado.
- Use `if` para condições mais complexas com operadores lógicos (`&&`, `||`, `!`).

---

📚 **Fontes:**  
[GitBook Java - DIO](https://felipe-aguiar.gitbook.io/dio-java/gitbook)  
[Oracle - Control Flow Statements](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/flow.html)
