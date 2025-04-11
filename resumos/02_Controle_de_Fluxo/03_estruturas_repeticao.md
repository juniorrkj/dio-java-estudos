# 🔁 Estruturas de Repetição em Java

As **estruturas de repetição** (loops) permitem executar um bloco de código várias vezes enquanto uma condição for verdadeira.

---

## 🔂 Tipos de loops

| Estrutura     | Quando usar                              |
|---------------|-------------------------------------------|
| `for`         | Quando se sabe o número de repetições     |
| `while`       | Quando a condição é verificada antes      |
| `do-while`    | Quando a condição é verificada depois     |

---

## 🔁 `for`

```java
for (int i = 0; i < 5; i++) {
    System.out.println("i = " + i);
}
```

---

## 🔁 `while`

```java
int i = 0;

while (i < 5) {
    System.out.println("i = " + i);
    i++;
}
```

---

## 🔁 `do-while`

```java
int i = 0;

do {
    System.out.println("i = " + i);
    i++;
} while (i < 5);
```

---

📚 **Fontes:**  
[Oracle - Loops](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/while.html)  
[W3Schools - Java Loops](https://www.w3schools.com/java/java_while_loop.asp)
