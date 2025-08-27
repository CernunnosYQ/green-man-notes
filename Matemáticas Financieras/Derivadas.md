#Cálculo #Matemáticas 
# Derivadas

En matemáticas, la derivada de una función $\large{f(x)}$ en un punto $\large{x_0}$ es la velocidad a la que cambia el valor de la función cuando se acerca al valor de $\large{x_0}$. En otras palabras, la derivada mide la rapidez con la que cambia la función en un determinado punto, siendo esta la pendiente de la recta tangente a la curva en el [[Límites|límite]] del punto $\large{x_0}$.

**Fórmula:** 
$$
\large {f'(x) = \lim_{h \to 0} \left[ \frac{f(x+h) - f(x)}{h} \right]}
$$

De lo anterior se derivan las siguientes reglas de derivación:

|         **Operación**          |            **Derivada**            |        **Operación**         |           **Derivada**           |
| :----------------------------: | :--------------------------------: | :--------------------------: | :------------------------------: |
|        Constante ($c$)         |                $0$                 |       Seno ($\sin{x}$)       |            $\cos{x}$             |
|         Variable ($x$)         |                $1$                 |      Coseno ($\cos{x}$)      |            $-\sin{x}$            |
|    Suma y resta ($u \pm v$)    |            $u' \pm v'$             |     Tangente ($\tan{x}$)     |           $\sec^2{x}$            |
|     Producto ($u \cdot v$)     |             $u'v+uv'$              |    Cotangente ($\cot{x}$)    |           $-\csc^2{x}$           |
|     División ($u \div v$)      |   $\large \frac{u'v - uv'}{v^2}$   |     Secante ($\sec{x}$)      |        $\sec{x} \tan{x}$         |
|        Potencia ($u^v$)        |             $vu^{v-1}$             |    Cosecante ($\csc{x}$)     |        $-\csc{x} \cot{x}$        |
|      Exponencial ($e^x$)       |               $e^x$                |   Arco seno ($\arcsin{x}$)   | $\large \frac{1}{\sqrt{1-x^2}}$  |
|    Logaritmo ($\log_u{x}$)     | $\large \frac{1}{x \cdot \log{u}}$ |  Arco coseno ($\arccos{x}$)  | $\large \frac{-1}{\sqrt{1-x^2}}$ |
| Logaritmo neperiano ($\ln{x}$) |           $\frac{1}{x}$            | Arco tangente ($\arctan{x}$) |    $\large \frac{-1}{1-x^2}$     |
## Regla de la cadena

La más útil de las reglas de derivación es la regla de la cadena que nos permite calcular derivadas de funciones compuestas

**Formula:**
$$\large u=f(v) \rightarrow u' = f'(v) \cdot v' $$
Una descripción más completa [[Regla de la cadena (Derivadas)|aquí]].