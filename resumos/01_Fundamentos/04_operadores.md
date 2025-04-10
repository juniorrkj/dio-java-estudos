# ➕ Operadores em Java

Os **operadores** em Java são símbolos especiais usados para realizar operações em variáveis e valores. Eles são fundamentais para a construção de expressões lógicas, aritméticas e de controle.

---

## 🧮 1. Operadores Aritméticos

Realizam operações matemáticas comuns.

| Operador | Descrição        | Exemplo        |
|----------|------------------|----------------|
| `+`      | Adição           | `a + b`        |
| `-`      | Subtração        | `a - b`        |
| `*`      | Multiplicação    | `a * b`        |
| `/`      | Divisão          | `a / b`        |
| `%`      | Módulo (resto)   | `a % b`        |

```java
int a = 10, b = 3;
System.out.println(a + b); // 13
System.out.println(a % b); // 1
```

---

## 🔁 2. Operadores de Incremento e Decremento

| Operador | Descrição       | Exemplo        |
|----------|-----------------|----------------|
| `++`     | Incrementa 1     | `a++` ou `++a` |
| `--`     | Decrementa 1     | `a--` ou `--a` |

```java
int x = 5;
System.out.println(x++); // imprime 5, depois x = 6
System.out.println(++x); // x = 7, imprime 7
```

---

## 🧮 3. Operadores Relacionais

Usados para comparar valores. Retornam `true` ou `false`.

| Operador | Descrição          | Exemplo        |
|----------|--------------------|----------------|
| `==`     | Igual a            | `a == b`       |
| `!=`     | Diferente de       | `a != b`       |
| `>`      | Maior que          | `a > b`        |
| `<`      | Menor que          | `a < b`        |
| `>=`     | Maior ou igual     | `a >= b`       |
| `<=`     | Menor ou igual     | `a <= b`       |

```java
System.out.println(10 > 5);  // true
System.out.println(10 != 10); // false
```

---

## 🧠 4. Operadores Lógicos

| Operador | Nome              | Exemplo        |
|----------|-------------------|----------------|
| `&&`     | E lógico (AND)    | `a > b && c > d` |
| `||`     | OU lógico (OR)    | `a > b || c > d` |
| `!`      | NÃO lógico (NOT)  | `!(a > b)`       |

```java
boolean cond1 = true;
boolean cond2 = false;
System.out.println(cond1 && cond2); // false
System.out.println(cond1 || cond2); // true
System.out.println(!cond1);         // false
```

---

## 🧾 5. Operadores de Atribuição

Atribuem valores às variáveis.

| Operador | Descrição               | Exemplo        |
|----------|-------------------------|----------------|
| `=`      | Atribuição simples      | `a = 5`        |
| `+=`     | Soma e atribui          | `a += 3`       |
| `-=`     | Subtrai e atribui       | `a -= 2`       |
| `*=`     | Multiplica e atribui    | `a *= 4`       |
| `/=`     | Divide e atribui        | `a /= 2`       |
| `%=`     | Módulo e atribui        | `a %= 3`       |

---

## 🧩 6. Operador Ternário

É uma forma reduzida de um `if-else`.

```java
int idade = 20;
String status = (idade >= 18) ? "Maior de idade" : "Menor de idade";
System.out.println(status); // Maior de idade
```

---

## ✅ Boas Práticas

- Utilize parênteses para deixar expressões mais claras.
- Evite encadeamentos lógicos muito complexos em uma só linha.
- Comente operações complexas para facilitar manutenção do código.

---

## 📚 Fontes

- [W3Schools - Java Operators](https://www.w3schools.com/java/java_operators.asp)
- [Oracle Java Tutorial - Operators](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/operators.html)
- [Baeldung - Java Operators](https://www.baeldung.com/java-operators)
