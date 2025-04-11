# 🔄 Conceito de Controle de Fluxo

O **controle de fluxo** em Java define a ordem em que as instruções de um programa são executadas. Ele permite **desvios condicionais, repetições e tratamento de exceções**.

---

## 🧠 Tipos principais

| Tipo                  | Descrição                             |
|-----------------------|----------------------------------------|
| Condicional           | Executa um bloco de acordo com condição (`if`, `switch`) |
| Repetição (loop)      | Repete um bloco (`for`, `while`, `do-while`) |
| Exceção               | Captura e trata erros em tempo de execução (`try`, `catch`, `throw`) |

---

## 🔁 Por que é importante?

- Torna o programa **dinâmico e flexível**
- Permite **tomada de decisão**
- Facilita a **interação com o usuário**

---

## 🧭 Exemplo simples

```java
int idade = 18;

if (idade >= 18) {
    System.out.println("Pode dirigir");
} else {
    System.out.println("Não pode dirigir");
}
```

---

📚 **Fontes:**  
[GitBook Java - DIO](https://felipe-aguiar.gitbook.io/dio-java/gitbook)  
[Oracle - Flow Statements](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/flow.html)
