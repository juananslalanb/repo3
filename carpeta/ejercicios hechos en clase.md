# 📘 Actividad de Análisis y Solución de Algoritmos

# 📚 Análisis y Desarrollo de Algoritmos

### 🔍 Algoritmos Secuenciales y Condicionales

---

*Resolución de problemas, análisis de procedimientos y elaboración de diagramas de flujo.*

---

# 📖 Situaciones de Ejemplo

---

## 🟦 Situación/Ejemplo 1

### 💼 Cálculo del Ingreso Semestral de un Empleado

---

### 📝 Planteamiento

> Estudiemos el siguiente problema y planteemos una solución utilizando un algoritmo secuencial.

**Problema:**

* Diseñar un algoritmo que reciba como información el **ID del empleado** y sus **seis primeros salarios del año**, para calcular el ingreso total obtenido durante el primer semestre y el promedio mensual. Al finalizar, se deben mostrar el ID, el ingreso total y el promedio mensual.

---

### ✅ Solución

> El procedimiento inicia solicitando el **ID del empleado** y los seis salarios correspondientes a los primeros meses del año (**S1, S2, S3, S4, S5 y S6**).
>
> Luego, se suman los seis valores para obtener el **Ingreso Total (IT)** correspondiente al semestre.
>
> Después, se divide el ingreso total entre seis para calcular el **Promedio Mensual (PM)**.
>
> Finalmente, se presentan el **ID del empleado**, el **ingreso total semestral** y el **promedio mensual**, dando por terminado el algoritmo.

---

### 🖼️ Diagrama de Flujo

**Representación gráfica del proceso mediante un diagrama de flujo.**

---

### 📥 Datos de Entrada

| **NOMBRE** | **DEFINICIÓN**                      | **TIPO** | **UNIDAD** |
| ---------- | ----------------------------------- | -------- | ---------- |
| ID         | Identificación del empleado         | Entero   | -          |
| S1-S6      | Salarios de los primeros seis meses | Real     | $          |

---

### 📤 Datos de Salida

| **NOMBRE** | **DEFINICIÓN**                     | **TIPO** | **UNIDAD** |
| ---------- | ---------------------------------- | -------- | ---------- |
| ID         | Identificación del empleado        | Entero   | -          |
| IT         | Total de ingresos del semestre     | Real     | $          |
| PM         | Promedio de los salarios mensuales | Real     | $          |

---





<img width="242" height="722" alt="ejercicio1" src="https://github.com/user-attachments/assets/36d13923-8dba-4b0f-9dda-335f511ef344" />

## 🟦 Situación/Ejemplo 2

### 🎂 Cálculo de Edad y Comprobación de Cumpleaños

---

### 📝 Planteamiento

> Analicemos la situación presentada y construyamos una solución mediante un algoritmo secuencial y condicional.

**Problema:**

* Elaborar un algoritmo que reciba la **fecha de nacimiento** de una persona, indicando año, mes y día, junto con la **fecha actual**. El algoritmo debe calcular la edad de la persona y establecer si ya cumplió años durante el año actual. Al terminar, deberá mostrar la edad y un mensaje que indique si el cumpleaños ya pasó o si todavía no ha llegado.

---

### ✅ Solución

> En primer lugar, el algoritmo solicita el año, mes y día de nacimiento, además de los datos correspondientes a la fecha actual.
>
> A continuación, se obtiene una edad inicial mediante la resta entre el año actual y el año de nacimiento.
>
> Posteriormente, se comparan el mes y el día actuales con los datos de nacimiento para determinar si la fecha de cumpleaños ya ocurrió.
>
> Cuando el mes actual es posterior al mes de nacimiento, se determina que la persona ya cumplió años y se conserva la edad calculada.
>
> Si los meses son iguales, se compara el día actual con el día de nacimiento. Si el día actual es igual o mayor, también se considera que ya cumplió años.
>
> Si ninguna de estas condiciones se cumple, se determina que el cumpleaños todavía no ha ocurrido.
>
> Finalmente, se presenta la información obtenida y el algoritmo finaliza.

---

### 🖼️ Diagrama de Flujo

**Representación gráfica del procedimiento para calcular la edad y verificar el cumpleaños.**

---

### 📥 Datos de Entrada

| **NOMBRE** | **DEFINICIÓN**                        | **TIPO** | **UNIDAD** |
| ---------- | ------------------------------------- | -------- | ---------- |
| Año_N      | Año en que nació la persona           | Entero   | -          |
| Año_A      | Año correspondiente a la fecha actual | Entero   | -          |
| Mes_N      | Mes de nacimiento                     | Entero   | -          |
| Mes_A      | Mes actual                            | Entero   | -          |
| Día_N      | Día de nacimiento                     | Entero   | -          |
| Día_A      | Día actual                            | Entero   | -          |

---

### 📤 Datos de Salida

| **NOMBRE** | **DEFINICIÓN**                              | **TIPO** | **UNIDAD** |
| ---------- | ------------------------------------------- | -------- | ---------- |
| Cumple_Hb  | Indicación de si la persona ya cumplió años | -        | -          |

---




<img width="602" height="902" alt="imagen2" src="https://github.com/user-attachments/assets/e3761dcd-e37f-4eb5-bd6d-0440d1d63f88" />

# 🧩 Ejercicios de Práctica

---

## 🟩 Ejercicio 3

### 🐠 Capacidad de un Acuario

---

### 📝 Problema

> Un acuario necesita conocer qué cantidad de agua puede contener. El usuario podrá decidir si desea obtener el resultado en **litros o galones**, mientras que las dimensiones del acuario solamente se pueden medir utilizando una cinta métrica en centímetros. Diseñar un algoritmo que permita solucionar esta situación.

---

### ✅ Solución

> Para comenzar, se deben ingresar las dimensiones del acuario expresadas en centímetros: **largo, ancho y alto**. También se debe indicar la unidad en la que se desea obtener el resultado.
>
> Con las medidas proporcionadas se calcula el volumen total del acuario y posteriormente se convierte dicho valor a litros.
>
> Si el usuario selecciona los galones como unidad de medida, se realiza la conversión correspondiente.
>
> Para finalizar, el algoritmo presenta la capacidad del acuario junto con la unidad seleccionada por el usuario.

---

### 🖼️ Diagrama de Flujo

**Representación gráfica del procedimiento para calcular la capacidad del acuario.**

---

### 📥 Datos de Entrada

| **NOMBRE** | **DEFINICIÓN**                    | **TIPO** | **UNIDAD** |
| ---------- | --------------------------------- | -------- | ---------- |
| FormaTnq   | Característica o forma del tanque | Flotante | -          |
| Largo      | Medida longitudinal del acuario   | Entero   | cm         |
| Alto       | Medida de altura del acuario      | Entero   | cm         |
| Ancho      | Medida del ancho del acuario      | Entero   | cm         |


<img width="682" height="1242" alt="imagen3" src="https://github.com/user-attachments/assets/0ffbd601-9174-41c8-8d10-51382c3c1897" />




---

### 📤 Datos de Salida

| **NOMBRE**            | **DEFINICIÓN**                              | **TIPO** | **UNIDAD** |
| --------------------- | ------------------------------------------- | -------- | ---------- |
| Capacidad del Acuario | Cantidad de agua que puede contener         | -        | -          |
| Unidad de medida      | Unidad utilizada para expresar la capacidad | -        | -          |

---

## 🟩 Ejercicio 4

### ✏️ Compra de Lápices

---

### 📝 Problema

> Elaborar un algoritmo que permita conocer el valor total que se debe pagar por una determinada cantidad de lápices. Cuando la compra sea de **1.000 unidades o más**, cada lápiz tendrá un valor de **$85**. Si se compran menos de 1.000 unidades, cada lápiz tendrá un precio de **$90**.

---

### ✅ Solución

> Primero se solicita al usuario la cantidad de lápices que desea adquirir.
>
> Después, el algoritmo comprueba si el número de lápices es **mayor o igual a 1.000**.
>
> Si se cumple esta condición, se establece un precio de **$85 por unidad**.
>
> Si la cantidad es inferior a 1.000, se utiliza un precio de **$90 por lápiz**.
>
> Finalmente, se multiplica la cantidad de lápices por el precio asignado para obtener el **total de la compra**, y se muestra el resultado.

---

### 🖼️ Diagrama de Flujo

**Representación gráfica del procedimiento para seleccionar el precio y calcular el total.**

---

### 📥 Datos de Entrada

| **NOMBRE**       | **DEFINICIÓN**                          | **TIPO** | **UNIDAD** |
| ---------------- | --------------------------------------- | -------- | ---------- |
| Cantidad_Lapices | Número de lápices que se desean comprar | Entero   | -          |

---

### 📤 Datos de Salida

| **NOMBRE** | **DEFINICIÓN**                               | **TIPO** | **UNIDAD** |
| ---------- | -------------------------------------------- | -------- | ---------- |
| TotalPagar | Valor total que debe pagarse por los lápices | Flotante | $          |

---






<img width="531" height="892" alt="ejercicio4" src="https://github.com/user-attachments/assets/ee2e3c3e-8882-4be7-b978-91fbc5cfd0fd" />

## 🟩 Ejercicio 5

### 👕 Descuento en Almacén de Ropa

---

### 📝 Problema

> Un establecimiento dedicado a la venta de ropa ofrece un descuento especial. Para compras cuyo valor sea **superior a $250.000**, se aplicará una reducción del **15%**. Para las compras que no superen este valor, se aplicará un descuento del **8%**.

---

### ✅ Solución

> El algoritmo comienza solicitando el **valor total de la compra**.
>
> Posteriormente, se verifica si el valor ingresado es mayor a **$250.000**.
>
> Si la compra supera dicha cantidad, se calcula un descuento equivalente al **15%** del valor total.
>
> En caso de que la compra sea igual o inferior a $250.000, se aplica un descuento del **8%**.
>
> Después se calcula el valor final que debe pagar el cliente, restando el descuento al precio original.
>
> Finalmente, se muestran el **valor del descuento** y el **total a pagar**.

---

### 🖼️ Diagrama de Flujo

**Representación gráfica del proceso para determinar el descuento y el valor final de la compra.**

---

### 📥 Datos de Entrada

| **NOMBRE**   | **DEFINICIÓN**                     | **TIPO** | **UNIDAD** |
| ------------ | ---------------------------------- | -------- | ---------- |
| Total_compra | Valor total de la compra realizada | Entero   | $          |

---

### 📤 Datos de Salida

| **NOMBRE** | **DEFINICIÓN**                              | **TIPO** | **UNIDAD** |
| ---------- | ------------------------------------------- | -------- | ---------- |
| TotalPagar | Valor final después de aplicar el descuento | Flotante | $          |
| Descuento  | Cantidad de dinero descontada               | Flotante | $          |

---

## 🟩 Ejercicio 4

### 🚌 Viaje de Estudios

---

### 📝 Problema

> El encargado de una institución educativa está preparando un viaje escolar y necesita calcular **cuánto debe pagar cada estudiante** y **cuál será el valor total que deberá cancelar la institución a la empresa de viajes**.

---

### ✅ Solución

> Para solucionar el problema, primero se debe conocer la **cantidad de estudiantes** que participarán en el viaje.
>
> Con base en el número de alumnos se determina el costo correspondiente del servicio ofrecido por la compañía de viajes.
>
> Una vez establecido el precio por estudiante, se calcula el valor total multiplicando el número de alumnos por el costo individual.
>
> Finalmente, el algoritmo muestra cuánto debe pagar cada estudiante y cuál es el costo total del servicio para la institución.

---

### 🖼️ Diagrama de Flujo

**Representación gráfica del procedimiento utilizado para calcular el costo individual y el valor total del viaje.**

---

### 📥 Datos de Entrada

| **NOMBRE**       | **DEFINICIÓN**                                     | **TIPO** | **UNIDAD** |
| ---------------- | -------------------------------------------------- | -------- | ---------- |
| Cantidad_Alumnos | Número de estudiantes que participarán en el viaje | Entero   | -          |

---

### 📤 Datos de Salida

| **NOMBRE** | **DEFINICIÓN**                                | **TIPO** | **UNIDAD** |
| ---------- | --------------------------------------------- | -------- | ---------- |
| TotalPagar | Valor total que se debe pagar por el servicio | Flotante | $          |








---

# 🎯 Fin de la Actividad

**Desarrollo y análisis de algoritmos secuenciales y condicionales mediante la solución de diferentes situaciones problema y su representación utilizando diagramas de flujo.**


