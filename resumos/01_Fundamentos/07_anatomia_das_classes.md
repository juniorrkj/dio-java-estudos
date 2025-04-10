# 🧬 Anatomia das Classes em Java

Em Java, uma **classe** é a estrutura básica que define um **tipo de objeto**. Ela agrupa atributos (dados) e métodos (comportamentos).

---

## 🧱 Estrutura básica de uma classe

```java
public class Pessoa {
    String nome;
    int idade;

    public void apresentar() {
        System.out.println("Olá, meu nome é " + nome);
    }
}
```

---

## 🧩 Componentes de uma classe

| Componente      | Exemplo                  | Descrição                                 |
|------------------|---------------------------|---------------------------------------------|
| Modificador de acesso | `public`, `private`     | Controla visibilidade da classe/membros     |
| Nome da classe   | `Pessoa`                 | Deve começar com maiúscula (CamelCase)     |
| Atributos        | `String nome`            | Características do objeto                  |
| Métodos          | `void apresentar()`      | Ações do objeto                            |
| Construtor       | `Pessoa()`               | Inicializa o objeto                        |

---

## 🧠 Boas práticas

- Nome de classe deve ser substantivo e começar com **letra maiúscula**
- Mantenha atributos como `private` e use métodos para acessar
- Uma classe = uma responsabilidade

---

## ✅ Exemplo completo

```java
public class Produto {
    private String nome;
    private double preco;

    public Produto(String nome, double preco) {
        this.nome = nome;
        this.preco = preco;
    }

    public void exibirInformacoes() {
        System.out.println(nome + " custa R$" + preco);
    }
}
```

---

📚 **Fontes:**  
[GitBook Java - DIO](https://felipe-aguiar.gitbook.io/dio-java/gitbook)  
[Oracle - Classes and Objects](https://docs.oracle.com/javase/tutorial/java/javaOO/classes.html)
