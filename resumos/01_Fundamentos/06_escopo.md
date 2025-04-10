# 📦 Escopo em Java

**Escopo** define onde uma variável pode ser **acessada, lida ou modificada**. Em Java, o escopo é delimitado por blocos de código `{}`.

---

## 📌 Tipos de escopo

| Tipo           | Onde vive              | Acessível onde?           |
|----------------|------------------------|----------------------------|
| Escopo de classe | Fora de métodos        | Em toda a classe (atributos) |
| Escopo de método | Dentro de métodos      | Apenas dentro daquele método |
| Escopo de bloco  | Dentro de `{}`         | Apenas dentro do bloco     |

---

## 🧪 Exemplos

### 1. Escopo de classe

```java
public class Pessoa {
    String nome; // escopo de classe
}
```

### 2. Escopo de método

```java
public void falar() {
    String mensagem = "Olá"; // escopo do método
    System.out.println(mensagem);
}
```

### 3. Escopo de bloco

```java
if (true) {
    int x = 5; // escopo do bloco
    System.out.println(x);
}
// System.out.println(x); // Erro: x fora do escopo
```

---

## ⚠️ Cuidados comuns

- Variáveis **com o mesmo nome** em escopos diferentes podem causar confusão:
  ```java
  int idade = 30;
  if (true) {
      int idade = 25; // ERRO: já existe no escopo externo
  }
  ```

- Use `this.` para diferenciar entre variável local e atributo da classe:
  ```java
  public void setNome(String nome) {
      this.nome = nome; // this.nome é o atributo da classe
  }
  ```

---

📚 **Fontes:**  
[GitBook Java - DIO](https://felipe-aguiar.gitbook.io/dio-java/gitbook)  
[Oracle Java Scope Docs](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/variables.html)
