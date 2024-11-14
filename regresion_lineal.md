## ¿Qué es la Regresión Lineal?
La regresión lineal es un método estadístico utilizado para modelar la relación entre una variable dependiente y una o más variables independientes. Se utiliza para predecir el valor de la variable dependiente basándose en los valores de las variables independientes.

![image](https://github.com/user-attachments/assets/698b1a65-42e1-44e3-a803-ff4f1962c273)


### Casos que cubre
- Predicción de valores continuos: Es útil cuando se desea predecir un valor continuo, como precio, temperatura, etc.
- Relación lineal: Funciona bien cuando existe una relación lineal entre la variable dependiente y las variables independientes.
- Modelos simples y múltiples: Puede ser utilizado tanto para regresión lineal simple (una variable independiente) como para regresión lineal múltiple (varias variables independientes).

### Casos que no cubre
- Relaciones no lineales: No es adecuada cuando la relación entre las variables no es lineal.
- Datos categóricos: No es eficaz para predecir variables categóricas.
- Multicolinealidad: Si las variables independientes están altamente correlacionadas entre sí, la regresión lineal puede no funcionar bien. 

## Principio Matemático de la Regresión Lineal
La regresión lineal se basa en encontrar la mejor línea recta que se ajuste a los datos. Matemáticamente, la ecuación de la recta es:

![image](https://github.com/user-attachments/assets/286c775a-fd11-4451-aa40-0625eab124eb)


$$
Y = \beta_0 + \beta_1X_1 + \beta_2X_2 + \cdots + \beta_nX_n + \epsilon
$$

Donde:
- $$\ Y \$$ es la variable dependiente.
- $$\ X_1, X_2, \ldots, X_n \$$ son las variables independientes.
- $$\ \beta_0 \$$ es la intersección (el valor de $$\ Y \$$ cuando todas las $$\ X \$$ son 0).
- $$\ \beta_1, \beta_2, \ldots, \beta_n \$$ son los coeficientes de regresión que representan la pendiente de la línea.
- $$\ \epsilon \$$ es el término de error que representa la diferencia entre el valor predicho y el valor real.

El objetivo es minimizar el término de error para encontrar la mejor línea que se ajuste a los datos.

![image](https://github.com/user-attachments/assets/0de9d7d7-5b6b-42ef-a8b3-c3a203a3631a)


## Explicación sencilla
Imagina que tienes una caja de lápices de colores y quieres saber cuántos lápices caben en una caja dependiendo de su tamaño.
La regresión lineal es como dibujar una línea que te ayuda a predecir cuántos lápices caben en cajas de diferentes tamaños. 
Si tienes muchos datos sobre cuántos lápices caben en cajas pequeñas, medianas y grandes, puedes dibujar una línea que pase cerca de todos esos puntos. 
Esta línea te dice, más o menos, cuántos lápices caben en una caja de cualquier tamaño.
