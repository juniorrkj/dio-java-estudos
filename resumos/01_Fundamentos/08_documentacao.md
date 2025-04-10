# 📚 Documentação com Javadoc

A documentação em Java é feita com **Javadoc**, um formato de comentário especial que permite gerar documentação HTML automaticamente a partir do código.

---

## 📝 Estrutura do Javadoc

```java
/**
 * Descrição da classe ou método.
 * @author Nome
 * @version 1.0
 * @param parametro Descrição
 * @return Descrição do valor retornado
 */
```

---

## ✅ Exemplo prático

```java
/**
 * Classe que representa uma calculadora simples.
 * @author João
 * @version 1.0
 */
public class Calculadora {

    /**
     * Soma dois números inteiros.
     * @param a primeiro número
     * @param b segundo número
     * @return soma dos números
     */
    public int somar(int a, int b) {
        return a + b;
    }
}
```

---

## ⚙️ Gerar documentação

```bash
javadoc NomeArquivo.java
```

Isso criará uma pasta `doc/` com arquivos HTML da documentação.

---

## 📌 Boas práticas

- Documente **todas as classes públicas**.
- Comente métodos complexos e com muitos parâmetros.
- Atualize a documentação ao alterar a lógica.

---

📚 **Fontes:**  
[Oracle - Javadoc](https://docs.oracle.com/javase/8/docs/technotes/tools/windows/javadoc.html)  
[Baeldung - Java Comments](https://www.baeldung.com/java-comments)
