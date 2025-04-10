# 🖥️ Terminal e Argumentos em Java

Java permite **executar programas pelo terminal** e passar **argumentos via linha de comando** para métodos.

---

## ▶️ Execução via terminal

```bash
javac Main.java
java Main
```

---

## 🎒 Passando argumentos para o `main`

O método `main` pode receber **argumentos em um array de Strings**:

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Olá, " + args[0]);
    }
}
```

### Execução:

```bash
java Main João
# Saída: Olá, João
```

---

## 📌 Dicas

- `args.length` indica quantos argumentos foram passados.
- Faça validações antes de usar os argumentos:

```java
if (args.length > 0) {
    System.out.println("Argumento: " + args[0]);
} else {
    System.out.println("Nenhum argumento fornecido.");
}
```

---

📚 **Fontes:**  
[Oracle Java Command Line Args](https://docs.oracle.com/javase/tutorial/essential/environment/cmdLineArgs.html)  
[Stack Overflow - Java Args](https://stackoverflow.com/questions/890966/how-do-i-pass-command-line-arguments-to-a-java-program)
