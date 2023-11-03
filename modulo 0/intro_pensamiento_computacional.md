## 🚀 Introducción al pensamiento computacional

### 📘 1. Aplicando lógica

Lo principal que debemos entender en programación es el **"qué"** y el **"cómo"** de la resolución de un problema planteado.

- **Qué:** Implica plantear una solución a un problema determinado, a través del planteo de acciones que llevan a una posible solución final.
  
- **Cómo:** Toma como entrada el **"qué"** para llevar ese conjunto de acciones o pasos expresados en una hoja o gráfico a una serie de instrucciones en el lenguaje que se haya elegido.

En definitiva:

> 🧠 **Qué** = Saber cómo plantear una posible solución.  
> 💻 **Cómo** = Conocer un lenguaje de programación.

El **"Qué"** es el inicio: Es lo primero que debemos analizar o comprender, ya que no importa tener la mejor herramienta si no sabemos cómo usarla. La importancia del **"Qué"** es primordial antes de afrontar cualquier problema de programación, y aquí es donde la lógica de programación toma relevancia.

### 🧩 ¿Qué es la lógica de programación?

La lógica es la ciencia que estudia el proceso de razonar y los procesos asociados a la actividad del razonamiento. Este proceso de organización es una sucesión de pasos interconectados que, en su conjunto, conforman una proposición o planteo de una posible solución (similar a los algoritmos).

**Esquema a seguir:**

> **Lógica** ➡️ **Ordenar ideas** ➡️ **Proceso**

Un abordaje correcto para resolver un problema implica subdividir un problema en problemas más pequeños (atomización). Cada **"subproblema"** debe ser resuelto con una única actividad o tarea simple. Organizando y priorizando estas tareas, se puede abordar cada uno individualmente. Una vez completados todos, se alcanza la solución global al problema inicialmente planteado.

Tomando esta estrategia como base, avanzamos a la parte final de la lógica, referida al "Proceso", donde las ideas son ordenadas y organizadas, siendo este el **"qué"**.
  

## 🧩 2. Resolución de problemas

### 📌 Serie de Fibonacci

La **serie de Fibonacci** es una secuencia numérica donde cada elemento es la suma de los dos anteriores. Se inicia generalmente con 0 y 1.

Ejemplo de la serie:
0, 1, 1, 2, 3, 5, 8, 13, 21, ...

La relación matemática se define como:
F(n) = F(n-1) + F(n-2)

Con `F(0) = 0` y `F(1) = 1`.

#### 🔍 Detalles sobre la Serie de Fibonacci
- **a.1) Naturaleza de la serie**: Es una serie de números.
- **a.2) Tipo de números**: Son números naturales.
- **a.3) Longitud de la serie**: Es infinita.
- **a.4) Ejemplo finito**: 1, 1, 2, 3, 5, 8, 13, 21, 34

#### 🔧 Funcionamiento
- **b.1) Inicio**: Comienza en 1.
- **b.2) Crecimiento**: Se incrementa exponencialmente.
- **b.3) Incremento en la serie**: La serie aumenta al agregarse de a un nuevo valor en la misma.
- **b.4) Cálculo del nuevo valor**: El nuevo valor surge de la suma del último y penúltimo valor de la serie.

#### 📖 Interpretación
> **Nota**: Siendo “x” el último valor e “y” el anteúltimo.

- **c.1) Cálculo**: "z = x + y", donde "z" es el nuevo valor de la serie.
- **c.2) Repetición**: Repetir este cálculo en forma sucesiva 8 veces (para cumplir con el ejemplo finito antes mencionado).

En este proceso, podemos identificar una serie de etapas y actividades llevadas a cabo en las mismas. Podemos pensar que este proceso consiste en las siguientes etapas:

### 🔄 Proceso

- **ENTRADA** ➡️ **PROCESO** ➡️ **SALIDA**

- **Entrada:**

  - En el punto **"a"** se empieza a entender el problema. En esta etapa nos enfocamos en el **PROBLEMA** no en la solución de este. 
  - Para poder hacer el punto anterior, debemos identificar los elementos que lo compoinen y analizarlos. *Desglosamos el problema, tomando el todo, y lo subdividimos en pequeñas tareas.*
  - Luego de identificar cada uno de los elementos del problema, debe asignarles una importancia **(por la información que aportar)** y una urgencia **(la cantidad de atención que debemos prestarles)**. En el caso concreto, debe ser el elemento de análisis que mayor información nos da. En el ejemplo de lla serie de Fibonacci sería cuales son los números que componen la primera serie.

- **Proceso:**
  - En el punto **"b"**, nos enfocamos en generar opciones de solución. Ya debemos dejar de enfocarnos en el problema para buscar mejor alternativa de *SOLUCIÓN*. Enumeramos las opciones que nos permiten llegar a una solución en base a lo planteado en la fase anterior **(Entrada).**
  - Priorizamos las opciones para enfocarnos en las que nos acercan más a la construcción de la solución. 
  - Los enunciados que determinemos probablemente estén vinculados entre sí y deberán ser organizados según su solución. Un conjunto de enunciados debe apuntar a una única solución. Esto es común cuando hay múltiples soluciones posibles o cuando no se cuenta con información completa en la fase inicial.
  - Al final, el Proceso termina cuando se selecciona la mejor opción de solución y se cuenta con un conjunto de conceptos orientados a comprender el problema para llegar a una solución. 

- **Salida:**
  - En la fase de Salida, se propone la mejor solución a un problema previamente desglosado en la fase de Entrada y entendido en la fase de Proceso.
  - En esta etapa se aplica y materializa la solución, usando como ejemplo la serie de Fibonacci, se obtiene una fórmula matemática que la representa de forma genérica.
  - Es crucial realizar una evaluación de los resultados, una etapa que a menudo se pasa por alto.
  - La evaluación, en el contexto simple de la serie de Fibonacci, sería verificar que la fórmula propuesta se ajusta a la serie al ejecutarla 8 veces consecutivas.
  -  En situaciones más complicadas, se llevan a cabo casos de pruebas, ajustando los datos de entrada y verificando que los resultados son los esperados.
  -  Si cambiamos el requisito inicial a "mostrar los primeros 4 números de la serie de Fibonacci desde un número específico", debemos garantizar que la solución funcione con números como 1, 2 o 13.

### 🧪 Casos de prueba
- **Ingreso: 1** 
  - **Resultado**: 1, 1, 2, 3, 5

- **Ingreso: 2** 
  - **Resultado**: 2, 2, 4, 6, 10

- **Ingreso: 13** 
  - **Resultado**: 13, 13, 26, 39, 65

> [Nota]: Esta última serie no es estrictamente Fibonacci.

El proceso finalizaría dando por cerrado el problema, en caso de cumplir con los casos de prueba, o volviendo al inicio, en caso de haber detectado una falla en el planteo.

## 🖥️ 3. Algoritmos 

### 📝 3.1 Definición

Un algoritmo es una abstracción que consta de instrucciones para resolver un problema mediante una secuencia de pasos. A partir de ciertos datos de entrada, se produce una solución total o parcial. Varias soluciones parciales pueden combinarse para formar una solución completa, y cada solución parcial sigue siendo un algoritmo por sí misma.

## 🔍 Características de los Algoritmos 

- **Secuencialidad**: Un algoritmo procede paso a paso. Se caracteriza por tener etapas intermedias donde cada paso puede ser analizado por su estado, entradas y posibles salidas.
  
- **Atomicidad**: Los pasos intermedios se traducen en acciones que solucionan un único problema a la vez.
  
- **Abstracción**: Un algoritmo es una representación abstracta, lo que significa que es independiente de cómo se implementa. Por ejemplo, considerando nuestra solución para Fibonacci.

- **Solución Concreta**: Una opción es crear un programa que simplemente muestre la serie 1,1,2,3,5... Esta aproximación no se consideraría un algoritmo, dado que es una solución concreta y no abstracta.
  
- **Solución Genérica**: La solución ideal sería tener una fórmula que represente la serie de forma abstracta. La fórmula sería: `"anteúltimo_número + último_número = nuevo_número_de_la_serie"`.