# Reto B — Bucles en C#

## Investigación y comparación

### 1. ¿Cómo se declara la variable o el contador?

En C# podemos declarar el contador dentro del propio `for`:

`int i = 1`

`int` indica que la variable `i` es de tipo entero y `= 1` indica que su valor inicial es 1.

En Python no es necesario indicar explícitamente el tipo de la variable.

---

### 2. ¿Cómo se muestra información por consola?

En C# utilizamos:

`Console.WriteLine(i);`

Esto muestra el valor de `i` por consola.

En Python utilizaríamos:

`print(i)`

Por tanto, `Console.WriteLine()` realiza en este caso una función equivalente a `print()` en Python.

---

### 3. ¿Cómo se delimitan los bloques de código? Comparadlo con la indentación de Python.

En C# se utilizan llaves `{ }` para indicar dónde comienza y termina un bloque de código.

Por ejemplo:

```csharp
for (int i = 1; i <= 5; i++)
{
    Console.WriteLine(i);
}

### 4. ¿Qué símbolos o palabras cambian respecto al ejemplo en Python?

En Python:

```python
for i in range(1, 6):
    print(i)
```

En C#:

```csharp
for (int i = 1; i <= 5; i++)
{
    Console.WriteLine(i);
}
```

Las principales diferencias son:

- C# utiliza `int` para indicar que `i` es una variable de tipo entero.
- C# utiliza `;` para separar las partes del `for`.
- C# utiliza `i <= 5` para indicar que el bucle continúa mientras `i` sea menor o igual que 5.
- C# utiliza `i++` para aumentar el valor de `i` en 1 después de cada repetición.
- C# utiliza `{ }` para delimitar el bloque de código.
- C# utiliza `Console.WriteLine()` para mostrar información por consola.
- Python utiliza `range()` para establecer el recorrido.

---

### 5. ¿Qué decisiones o repeticiones se mantienen? Explicad el algoritmo en castellano, sin usar código.

El algoritmo comienza con un contador que tiene el valor 1.

En cada repetición se muestra el valor actual del contador y después se aumenta en una unidad.

El proceso continúa mientras el contador sea menor o igual que 5.

Cuando el contador supera el valor 5, el bucle termina.

Por tanto, aunque Python y C# utilizan una sintaxis diferente, ambos siguen el mismo algoritmo: empezar en 1, avanzar de uno en uno y terminar después de mostrar el número 5.

---

### 6. ¿Habéis necesitado algún elemento adicional para ejecutar el programa, como una función principal? Separadlo de la estructura que estáis investigando.

En C# podemos utilizar una clase `Program` y un método `Main` como punto de entrada del programa.

Por ejemplo:

```csharp
using System;

class Program
{
    static void Main()
    {
        for (int i = 1; i <= 5; i++)
        {
            Console.WriteLine(i);
        }
    }
}
```

El método `Main` y la clase `Program` forman parte de la estructura necesaria para ejecutar este tipo de programa.

El elemento que estamos investigando en este ejercicio es el bucle `for`, concretamente:

```csharp
for (int i = 1; i <= 5; i++)
{
    Console.WriteLine(i);
}
```