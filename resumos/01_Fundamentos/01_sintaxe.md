# 🧱 Sintaxe em Java

A **sintaxe** em Java define o conjunto de regras que determinam como programas devem ser escritos e estruturados. Aprender a sintaxe é o primeiro passo para criar códigos funcionais e organizados.

## 🗂 Estrutura Básica de um Programa Java

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Olá, mundo!");
    }
}
```

### Explicação:

- `public class HelloWorld`: Declara uma classe pública chamada `HelloWorld`.
- `public static void main(String[] args)`: Método principal, ponto de entrada da aplicação.
- `System.out.println(...)`: Imprime uma linha no terminal.

## 🧱 Componentes Essenciais da Sintaxe

| Elemento | Descrição |
|---------|-----------|
| `;`     | Fim de instruções |
| `{}`    | Delimita blocos de código |
| `()`    | Usado em chamadas de métodos e declarações de parâmetros |
| `//`    | Comentário de uma linha |
| `/* */` | Comentário de múltiplas linhas |

## 📏 Regras de Sintaxe

1. **Case Sensitive**: Java diferencia maiúsculas de minúsculas (`Variavel` ≠ `variavel`).
2. **Nomes de arquivos**: Devem ter o mesmo nome da classe pública (ex: `HelloWorld.java`).
3. **Cada instrução termina com ponto e vírgula (`;`)**.
4. **Os blocos de código devem ser delimitados por chaves `{}`**.

## 🛠 Boas Práticas de Sintaxe

- Use **indentação** para facilitar a leitura.
- Nomeie variáveis, classes e métodos de forma descritiva.
- Comente seu código com moderação e clareza.

## 💬 Exemplo com Comentários

```java
public class Calculadora {
    public static void main(String[] args) {
        // Soma dois números
        int resultado = 2 + 3;
        System.out.println("Resultado: " + resultado); // Saída: Resultado: 5
    }
}
```

## 🔗 Fontes recomendadas

- [Oracle Java Syntax Guide](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/index.html)
- [W3Schools - Java Syntax](https://www.w3schools.com/java/java_syntax.asp)
