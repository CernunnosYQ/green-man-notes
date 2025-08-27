#MatemáticasFinancieras 
# Conceptos clave descuentos

## Valor nominal o futuro ($F$)

Es el monto que se debe pagar en la fecha de vencimiento.  
- Es el valor sobre el cual se calcula el descuento.
- En un pagaré o letra de cambio, representa el monto total a recibir en el futuro.

## Valor presente ($P$)

Es el monto que se paga hoy para liquidar la obligación antes de la fecha de vencimiento.  
- Se obtiene restando el descuento del valor nominal: $\large P = F - D$  
- Dependiendo del tipo de descuento, la relación con la tasa varía:

  - **Descuento comercial (bancario):** se aplica directamente sobre el valor nominal. $$\large D_c = F \cdot d \cdot t, \quad P = F - D_c = F(1 - d \cdot t)$$
  - **Descuento racional (real):** se calcula sobre el valor presente, lo que lo hace equivalente a intereses simples sobre el capital. $$\large D_r = \frac{F \cdot d \cdot t}{1 + d \cdot t}, \quad P = F - D_r = \frac{F}{1 + d \cdot t} $$
## Descuento ($D$)

Es la reducción que se aplica al valor nominal por pagar anticipadamente.  
- Representa el “interés” que se descuenta por anticipado.  
- Fórmulas:  
  - Comercial: $\large D_c = F \cdot d \cdot t$  
  - Racional: $\large D_r = \frac{F \cdot d \cdot t}{1 + d \cdot t}$  

## Tiempo ($t$)

Es el periodo que falta hasta el vencimiento del valor nominal.  
- Puede medirse en años, meses o días según la unidad de la tasa de descuento.  
- Se puede usar año comercial ($360$ días) o año real ($365$ días) para convertir los días a fracción de año.

## Tasa de descuento ($d$)

> [!WARNING] Debe estar expresada en la misma unidad de tiempo que el periodo de cálculo

Es el porcentaje aplicado sobre el valor nominal o presente para calcular el descuento.  
- **Descuento comercial:** se aplica sobre el valor nominal.  
- **Descuento racional:** se aplica de forma que refleje el interés sobre el valor presente.