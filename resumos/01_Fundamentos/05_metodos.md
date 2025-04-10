# 🔧 Métodos em Java

Métodos representam **ações ou comportamentos**. Permitem reaproveitamento de código e organização lógica.

---

## 📌 Estrutura básica de um método

```java
modificador tipoRetorno nomeMetodo(parâmetros) {
    // corpo do método
}
```

### Exemplo:

```java
public int somar(int a, int b) {
    return a + b;
}
```

---

## 🧱 Componentes do método

| Parte             | Exemplo            | Significado                      |
|------------------|--------------------|----------------------------------|
| Modificador       | `public`           | Visibilidade                     |
| Tipo de retorno   | `int`              | Tipo do valor retornado          |
| Nome              | `somar`            | Nome do método (camelCase)       |
| Parâmetros        | `(int a, int b)`   | Valores de entrada               |
| Corpo             | `{ return a + b; }`| Instruções do método             |

---

## 🔁 Tipos de métodos

- **Com retorno:** retorna um valor (ex: `int`, `String`)
- **Sem retorno:** usa `void`

```java
public void exibirMensagem() {
    System.out.println("Olá, mundo!");
}
```

---

## 🧠 Boas práticas

- Nomeie métodos com verbos: `calcularMedia()`, `exibirMensagem()`
- Use `return` apenas se o método tiver tipo de retorno
- Mantenha o método curto e coeso (focado em uma ação)

---

## ✅ Exemplo prático

```java
public class Calculadora {
    public int multiplicar(int x, int y) {
        return x * y;
    }

    public void mostrarResultado(int resultado) {
        System.out.println("Resultado: " + resultado);
    }
}
```

---

📚 **Fontes:**  
[GitBook Java - DIO](https://felipe-aguiar.gitbook.io/dio-java/gitbook)  
[W3Schools - Java Methods](https://www.w3schools.com/java/java_methods.asp)  
[Oracle Docs - Methods](https://docs.oracle.com/javase/tutorial/java/javaOO/methods.html)
