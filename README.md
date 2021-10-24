# Calculadora de Areas

![image](https://user-images.githubusercontent.com/91550955/138615329-d5bb7b37-5075-416e-8007-c9351feb0186.png)

# Desarrollo

### 1. Análisis.

  En este primer paso estudiamos con detalle la situación, tratamos de comprender qué es lo que quiere el cliente y de definir como o que pretende hacerse para desarrollar el programa que se nos pide. En este caso se nos pide un programa con el cuál podamos calcular áreas de diferentes figuras geométricas, todas estas necesitan una formula indicada, ya que no todas son iguales. Para esto analizamos las diferentes fórmulas, en las cuales podemos ver que hay elementos repetidos o algunas operaciones son iguales pero con diferentes elementos. Aparte de esto miraremos diferentes programas o aplicaciones que existen para este propósito y poder hacernos una idea de como se estas están ideadas y desarrolladas.  Vemos que muchas tienen un diseño básico, ya que están diseñadas solo para realizar los cálculos.

### 2. Codificación.

En este paso ya hemos de poner a trabajar toda esa información y conocimiento que hemos recogido en la etapa de análisis, por ejemplo las fórmulas, por ejemplos las de las siguientes figuras:

**Cuadrado**

	base=solicitarValor("Indica la base o altura: ");
	System.out.println("\nEl area del cuadrado es " + (base*base));
								
Rectángulo

	base=solicitarValor("Indica la base: ");
altura=solicitarValor("Indica la altura: ");
	System.out.println("\nEl area del rectangulo es " + (base*altura));
								
Círculo

	radio=solicitarValor("Indica el radio: ");
	System.out.printf("\nEl area de la circunferencia es %1.2f\n", Math.PI*(Math.pow(radio,2)));			
				
Triángulo

	base=solicitarValor("Indica la base: ");
	altura=solicitarValor("Indica la altura: ");
	System.out.printf("\nEl area del triangulo es %1.2f\n", (base*altura)/2);

  Con una idea general desarrollamos el resto de fórmulas, aplicando diferentes bucles y funciones las cuales serán decididas por el usuario,  para este programa según lo visto en clase la mejor elección sería usar Python para realizar los cálculos. 
Por ejemplo en Python la formula para el triángulo será:


> print("Cálculo de area del triángulo")

>base=float(input("¿Cuál es la base?"))

>altura=float(input("¿Cuál es la altura?"))

>area=(base*altura)/2

>print(area)

>print("El área es "+str(area))



### 3. Diseño.
  Para este tipo de aplicaciones usamos un diseño no muy cargado para mejorar su funcionalidad y no tener un aspecto un “soso” que esté de acuerdo al gusto del cliente y usuario, ya que buscamos el equilibrio entre aspecto y funcionalidad, puesto que es una aplicación orientada al cálculo de áreas.


### 4. Pruebas.
  Estas pruebas aseguran el funcionamiento de la aplicación y que no encontramos ningún problema en el uso. Gracias a esto veremos si cumple los requisitos pedidos por el cliente, como el número de usuarios que aguanta o la velocidad con la que funciona el programa. Dando lugar al siguiente paso.

### 5. Despliegue.
  En este paso publicamos la aplicación y confirmamos a los primeros usuarios, es decir ponemos la aplicación a la venta o disponible para descargar.

### 6. Mantenimiento.
  Este paso será desarrollado periódicamente  por nuestra empresa o nosotros mismos para confirmar que la aplicación no sufre ningún fallo o posee algún tipo de inconveniente para los usuarios, ya sea por problemas de rendimiento o algún otro tipo de error.


Y con esto terminaríamos el proceso de creación de nuestro programa.
