# Proyecto-Grupo 7
   INTEGRANTES
- DOMENICA BELEN RODRIGUEZ NARANJO
- MAYDELEINE SAMIRA SANCHEZ MONROY
- SHEYLA ARLETTE TUMBACO MORÁN
# Estado
Semana 2 - Estructura base
12/06/26
Hoy nos reunimos y organizamos nuestro proyecto de la siguiente manera:
Decidimos hablar primero acerca sobre lo que haremos de proyecto, que en nuestro caso será sobre una automatización de gestión de procesos, en el cual implementaremos todo de acuerdo a la 
sugerencia de nuestro docente.

Realizamos las estructuras de carpetas en una hoja de cuaderno para poder guiarnos, esta carpeta estará dentro de la carpeta general del grupo, donde estarán "docs" que este es donde 
ubicaremos nuestra estructura en formato word y la archivaremos. La carpeta de "scr" es para agregar el main.py que será nuestro código completo, quisimos agregar esta carpeta solo para 
más organización, también aggregarmos una carpeta de "README.md", que será donde documentaremos nuestros avances. Todas estas carpetas serán llevadas a GITHUB para que nuestro docente
pueda visualizar nuestras carpetas, códigos y doccumentos. GITHUB nos ayuda a que guarde nuestro progreso en la nube, es seguro y eficiente.
 
También nos repartimos cada una que parte haremos para nuestro proyecto, se decidió que la capa de de "DATOS" será realizado por SHEYLA TUMBACO, que será la Capa 1.
Capa 2 de "FUNCIONES" será realizada por DOMENICA RODRIGUEZ.
Capa 3 de "MENÚ" será realizada por SAMIRA SANCHEZ.

Así que nos pusimos a charlar y compartir nuestras ideas. Decidimos hacer todo esto de acuerdo a lo que nos han enseñado, tomando en cuenta algunos conceptos para poder darle vida a nuestro
programa, así que investigamos más a fondo para que el programa sea más útil y completo.
Como haremos una automatización utilizaremos estas estructuras adicionales:

- import random: Nos pidieron que las parejas de estudiantes sea al azar. Para eso, decidimos usar import random y random.shuffle() que mezclará la lista de estudiantes. 
Sin esto, las parejas siempre serían las mismas, así que cada ves que el usuario elija la opción 1, saldrán parejas diferentes.

- while True: Nos va a permitir que nuestro menú se repita varias veces después de cada opción, permite que el bucle este activo. Sin este bucle si elegimos una opción ya no nos va a poder 
permitir seguir eligiendo más opciones y el programa acabaría en una sola opción.
Ayuda a que el usuario pueda hacer parejas, ver fechas, comparar notas y calcular el final, sin tener que abrir el programa cada vez.

Estas dos estructuras serán nuestro punto clave para poder realizar nuestra automatización de la mejor manera.

Hasta ahora es todo lo que tenemos para esta semana, vamos a hacer pruebas para nuesto programa, ver las posibles soluciones y fallas y ayudandonos mutuamente si se nos complica entender 
algo, aunque las dos partes de las estructuras será un reto para nosotras, haremos lo posible para que nuestro programa funcione completamente.

Semana 3 - Elaboración de Definciones del Proyecto
15/06/26
Esta semana nos enfocamos en crear nuestros Objetivos generales, específicos y los requerimientos de nuestro proyecto. Esta fue una tarea asignada por nuestro docente y se realizó de manera individual. 
Cada una describió cada punto requerido para el proyecto en base a nuestro diagrama.
Esta fue una de las formas en la que se describió los puntos:

Objetivo general: Desarrollar un sistema para gestionar procesos logísticos y de coherencia, optimizando el flujo de trabajo y mejorando la coordinación entre los participantes.

Objetivos específicos:

· Registrar estudiantes con nombre, correo e identificación
· Consultar, buscar, actualizar y eliminar estudiantes
· Generar parejas o grupos de manera aleatoria
· Reorganizar grupos automáticamente
· Registrar fechas importantes
· Gestionar tareas y actividades asignadas a grupos
· Consultar historial de asignaciones
· Comparar resultados entre actividades
· Calcular estadísticas básicas
· Menú interactivo con while True
· Validar datos ingresados
· Generar reportes
· Actualizar información sin reiniciar
· Registrar fecha y hora automáticamente

Requerimientos funcionales (30 en total):

· Gestión de estudiantes: registrar, consultar, buscar, actualizar, eliminar
· Gestión de grupos: generar parejas, crear grupos, evitar duplicados, consultar, reorganizar
· Gestión de actividades: registrar, asignar a grupos, consultar pendientes, marcar completadas, registrar observaciones
· Gestión de fechas: registrar, consultar próximas, validar, mostrar por fecha, registrar automáticamente
· Menú y validación: while True, múltiples operaciones, validar opciones, try/except
· Reportes: generar reportes, historial, comparar resultados, estadísticas, resumen general

Cuando empezamos a planificar el proyecto, leímos la rúbrica y pensamos que el proyecto iba a ser sobre registrar estudiantes con correo, identificación y gestionar actividades, con esa idea empezamos a trabajar.

Pero después, cuando nos pusimos a hacer el código, nos dimos cuenta de que muchas de esas cosas no las habíamos visto en clase y que sería muy complicado. Entonces volvimos a leer bien la rúbrica y vimos que en realidad el proyecto era más sencillo: solo había que hacer un sistema de comparación de notas entre evaluadores y asignación de parejas.

Sin embargo, aunque parecía más sencillo, también tuvimos dificultades porque agregamos varias líneas de código que no habíamos visto en clase, como import random, random.shuffle(), while True. Tuvimos que investigar por nuestra cuenta para poder implementarlas y que el programa funcionara correctamente, ya que de esta manera estas líneas de código al momento de investigar nos dimos cuenta de que era clave para generar la automatización. 

Nos dimos cuenta de que habíamos malinterpretado la tarea al principio, pero con esfuerzo y buscando información adicional logramos modificar nuestro código a tiempo.

Nuestros objetivos y requerimientos quedaron de la siguiente manera:

OBJETIVO PRINCIPAL

Crear un sistema automatizado para la gestión de evaluaciones docentes que permita:

· Asignar pares aleatorios para coevaluación
· Verificar la coherencia entre diferentes evaluadores
· Calcular promedios
· Mostrar un cronograma de entregas. Todo a través de un menú interactivo que se repita hasta que el usuario decida salir

---

OBJETIVOS ESPECÍFICOS

1. Gestión de Datos Básicos

· Mantener un catálogo de estudiantes con sus nombres
· Administrar las notas de cada estudiante provenientes de 3 evaluadores (Profesor 1, Profesor 2 y Autoevaluación)
· Almacenar las fechas de entrega de las evaluaciones

---

2. Gestión de Evaluaciones

· Registrar 3 notas por estudiante (Profesor 1, Profesor 2 y Autoevaluación)
· Comparar las notas de los diferentes evaluadores para detectar discrepancias
· Calcular automáticamente la diferencia emn porcentaje entre la nota más alta y la más baja
· Establecer el 20% para determinar si los evaluadores están de acuerdo
· Calcular la nota final: 40% Profesor 1, 40% Profesor 2, 20% Autoevaluación

---

3. Gestión de Coherencia

· Detectar automáticamente si los evaluadores están de acuerdo
· Identificar desaacuerdos mayores al 20% entre evaluadores
· Mostrar mensajes claros sobre el estado de la coherencia

---

4. Gestión de Coevaluación

· Asignar aleatoriamente pares de estudiantes para coevaluación
· Mostrar las parejas asignadas claramente
· Asegurar que ningún estudiante quede sin par (mostrar "Sin par" cuando corresponda)

---

5. Gestión de Tiempos

· Mostrar un cronograma claro de las fechas de entrega
· Presentar las fechas de forma ordenada y visual

---

6. Interfaz de Usuario

· Proporcionar un menú interactivo con opciones claras
· Mantener el menú activo hasta que el usuario decida salir
· Validar las opciones ingresadas por el usuario
· Mostrar mensajes de error para opciones inválidas

---

7. Arquitectura del Sistema

· Organizar el código en 3 capas:
  · Capa 1: Datos (estudiantes, evaluaciones)
  · Capa 2: Lógica (funciones de procesamiento)
  · Capa 3: Interfaz (menú interactivo)
· Mantener el código limpio y estructurado

---
Semana 4 - Prototipo de Capa 1 y 2 sin LLM. Código que carga datos y ejecuta la lógica central (versión mosk)
19/06 - 22/06
Entre estás fechas nos dedicamos a agregar la capa 1 y 2 en nuestro código de automatización, luego de corregir nuestro error empezamos desde 0.
CAPA 1: Se muestran los datos, se utilizó lista para agregar los nombres de cada estudiante, elegimos 5 estudiantes.
También agregamos un diccionario para poner las calificaciones que se requieren de acuerdo a las indicaciones de nuestro proyecto, que son nota_profesor1, nota_profesor2, autoevaluacion.

CAPA 2: Utilizamos def para crear nuestras funciones, creamos la línea de código def asignar_pares():
Esto significa que la función recibe una lista de estudiantes como variables, en donde debajo se colocará:
pares = [] 
Que servirá para almacenar los pares de estudiantes.

Debajo de esta sigue cantidaad = len(lista), nos ayudará a obtener la cantidad de estudiantes en nuestra lista.
Procedemos con la función for i in range, esta función va ayudarnos a recorrer nuestra lista de estudiantes en dos en dos, de manera par.
Entonces quedaría for i in range(0, cantidad, 2):
0 es solo porque el rango inicia en 0, termina en la cantidad de estudiantes y se incrementa de 2 en 2.

if i + 1 < cantidad:
            pares.append((lista[i], lista[i + 1]))
        else:
            pares.append((lista[i], "Sin par"))
Nos pregunta si existe un estudiante en la posición i + 1, i es la posición que va cambiando, i puede ser 1,2,3.. 
Nos dice; Si i + 1 es.. significa la posición de al lado de por ejemplo Ana es Luis.
Entonces agregamos pares.append, que nos agregará la pareja de la lista de pares, esta en nuestro código para guardar la pareja completa y el .append es el que agrega un elemento final de la lista.
¿Por qué el sin par?
Esta para que la persona no quede olvidada, nos indica que si no hay un compañero que asigne que es "Sin par".
Entonces haremos que nos devuelva la lista utilizando:
return pares
Para que el menú pueda mostrar el resultado
Ahora  mostraremos las fechas de entragas y del proyecto
def mostrar_fechas():
    print(" * Tarea 1: 20/06/2026")
    print(" * Tarea 2: 27/06/2026")
    print(" * Proyecto: 10/07/2026")
Vamos a calcular la diferncia en porcentaje entre la nota más baja y alta, utilizando primero la función de:
def calcular_diferencia(n1, n2, n3):
    if n1 >= n2 and n1 >= n3:
        mayor = n1
    elif n2 >= n1 and n2 >= n3:
        mayor = n2
    else:
        mayor = n3
Nos dice si la nota1 es mayor a nota2 y nota1 es mayor a nota3 ento


