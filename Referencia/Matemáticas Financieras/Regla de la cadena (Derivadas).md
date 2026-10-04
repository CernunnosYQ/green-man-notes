#Cálculo #Matemáticas 
# Regla de la cadena

La regla de la cadena es una herramienta fundamental en matemáticas para encontrar la [[Derivadas|derivada]] de una función compuesta.

Supongamos que tenemos dos funciones, $\large u=f(v)$ y $\large v=g(x)$. La regla de la cadena nos permite encontrar la derivada de la función compuesta $\large u=f(v)$ con respecto a la variable $\large x$.

La regla se expresa como:$$\large
\frac{dx}{du}​=\frac{dv}{du}​\cdot \frac{dx}{dv}
$$​
Donde $\large \frac{dv}{du}$​ es la derivada de la función $\large u=f(v)$ con respecto a $\large v$, y $\large \frac{dx}{dv}$​ es la derivada de la función $\large v=g(x)$ con respecto a $\large x$.

**Ejemplo:**

Supongamos que queremos encontrar la derivada de la función compuesta:
$$\large y=\sin{x^2}$$
Primero, encontramos las derivadas individuales:

- La derivada de $\large \sin{u}$ es $\large \cos{u}\cdot u′$.
- La derivada de $\large u=x^2$ es $\large 2x$.

Ahora, aplicamos la regla de la cadena:
$$\large y′=\frac{dx}{du}​=\cos{x^2}\cdot 2x$$

La regla de la cadena nos permite encontrar la derivada de una función compuesta simplemente multiplicando las derivadas individuales.