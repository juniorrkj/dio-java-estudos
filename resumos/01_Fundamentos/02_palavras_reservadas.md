# 🔒 Palavras Reservadas em Java

Palavras reservadas são termos da linguagem Java que **não podem ser usados como nomes de variáveis, métodos ou classes**, pois já têm significado especial na linguagem.

---

## 📃 Lista das principais palavras reservadas

```text
abstract   continue   for           new        switch
assert     default    goto*         package    synchronized
boolean    do         if            private    this
break      double     implements    protected  throw
byte       else       import        public     throws
case       enum       instanceof    return     transient
catch      extends    int           short      try
char       final      interface     static     void
class      finally    long          strictfp   volatile
const*     float      native        super      while
```

🔸 `*` As palavras `const` e `goto` existem, mas não são usadas no Java moderno.

---

## ⚠️ Regras

- São **case-sensitive**: `if` é válido, `IF` não.
- Não podem ser usadas para nomear variáveis, métodos ou classes:
  ```java
  int class = 10; // Erro!
  ```

---

## ✅ Exemplo correto

```java
public class Pessoa {
    private String nome;
    private int idade;

    public void imprimirDados() {
        System.out.println(nome + " - " + idade);
    }
}
```

---

📚 **Fonte:**  
[GitBook Java - Felipe Aguiar (DIO)](https://felipe-aguiar.gitbook.io/dio-java/gitbook)  
[Documentação Oracle](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/_keywords.html)
