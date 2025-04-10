# 🔢 Tipos e Variáveis em Java

Variáveis são espaços de memória para armazenar dados. Em Java, todas as variáveis precisam ser **declaradas com um tipo**.

---

## 🧱 Tipos Primitivos

| Tipo     | Descrição            | Exemplo       |
|----------|----------------------|---------------|
| `int`    | Inteiro              | `int idade = 25;` |
| `double` | Número com decimais  | `double peso = 70.5;` |
| `char`   | Caractere            | `char letra = 'A';` |
| `boolean`| Verdadeiro/falso     | `boolean ativo = true;` |

Outros: `byte`, `short`, `long`, `float`.

---

## 📦 Tipos por Referência (Classes)

São objetos e possuem métodos. Exemplo: `String`, `Scanner`, `List`.

```java
String nome = "João";
```

---

## 📝 Declaração de Variáveis

```java
tipo nome = valor;
```

Exemplo:
```java
int idade = 20;
boolean aprovado = true;
```

---

## 📌 Regras de nomes válidos

- Pode conter letras, números, `_` e `$`.
- Não pode começar com número.
- Não pode usar palavras reservadas.
- Use camelCase para variáveis: `mediaFinal`, `quantidadeAlunos`.

---

## 💡 Dicas

- Sempre dê nomes descritivos às variáveis.
- Use `final` para declarar constantes:
  ```java
  final double PI = 3.14;
  ```

---

## ✅ Exemplo prático

```java
public class VariaveisExemplo {
    public static void main(String[] args) {
        int idade = 30;
        double salario = 2500.50;
        boolean ativo = true;

        System.out.println("Idade: " + idade);
        System.out.println("Salário: " + salario);
        System.out.println("Ativo: " + ativo);
    }
}
```

---

📚 **Fonte:**  
[GitBook Java - Felipe Aguiar (DIO)](https://felipe-aguiar.gitbook.io/dio-java/gitbook)
