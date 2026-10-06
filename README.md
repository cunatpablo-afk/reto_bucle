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