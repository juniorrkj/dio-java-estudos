# ⚠️ Estruturas de Exceções em Java

**Exceções** são eventos que ocorrem durante a execução de um programa e interrompem o fluxo normal do código. Java trata esses eventos com **blocos de código específicos**.

---

## 🧱 Estrutura `try-catch`

```java
try {
    // código que pode gerar exceção
} catch (Exception e) {
    // tratamento da exceção
}
```

---

## ✅ Exemplo prático

```java
try {
    int resultado = 10 / 0;
} catch (ArithmeticException e) {
    System.out.println("Erro: divisão por zero.");
}
```

---

## 🔁 `finally`

Executa sempre, com ou sem erro.

```java
try {
    int[] arr = new int[2];
    arr[3] = 10;
} catch (ArrayIndexOutOfBoundsException e) {
    System.out.println("Índice inválido");
} finally {
    System.out.println("Finalizando...");
}
```

---

## 💣 `throw` e `throws`

### `throw`: lança uma exceção manualmente

```java
throw new IllegalArgumentException("Valor inválido");
```

### `throws`: indica que um método pode lançar exceção

```java
public void lerArquivo() throws IOException {
    // código
}
```

---

📚 **Fontes:**  
[Oracle - Exceptions](https://docs.oracle.com/javase/tutorial/essential/exceptions/index.html)  
[Baeldung - Java Exception Handling](https://www.baeldung.com/java-exceptions)
