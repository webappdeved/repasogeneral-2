
## Institución

**Institución:** E.E.S.T. N.º 1 “Eduardo Ader” — Vicente López  
**Curso:** 5.º año, 3.ª división  
**Grupos:** A-B  
**Materia:** Laboratorio de Programación (LPR)  
**Profesor:** Mansilla Muñoz, York Elías  
**Actividad:** Actividad 6 — Taller Práctico de Repaso y Consolidación en C++  
**Ciclo lectivo:** 2026

---

## Descripción del Proyecto

**REPASOGENERAL** es un proyecto académico desarrollado en C++ para la Actividad 6 de Laboratorio de Programación. Su objetivo es consolidar los conocimientos adquiridos durante el ciclo lectivo mediante una suite de ejercicios prácticos relacionados con la recursividad, la búsqueda secuencial y la manipulación de variables mediante punteros.

El programa reúne tres retos en una aplicación de consola. A través de ellos, se estudia el funcionamiento de las llamadas recursivas, el recorrido de arreglos en memoria contigua y la modificación de valores originales mediante el pasaje de direcciones de memoria y la desreferenciación.

El repositorio también permite organizar el código fuente, registrar las modificaciones, documentar el proceso de desarrollo y conservar evidencias de ejecución. Como parte de las actividades complementarias, se propone configurar Git para enviar los cambios a GitHub y GitLab mediante una estrategia de doble destino (*Dual-Remote*).

## Integrantes (Grupo N.º 03) (AGREGAR EL/LOS INTEGRANTE/S!)

- **Integrante 1:** [Apellido y nombre] — [Rol y tareas realizadas].
- **Integrante 2:** [Apellido y nombre] — [Rol y tareas realizadas].
- **Integrante 3:** [Apellido y nombre] — [Rol y tareas realizadas].
- **Integrante 4:** [Apellido y nombre] — [Rol y tareas realizadas].

*Completar con los integrantes reales del equipo y sus responsabilidades específicas.*

## Requisitos e Instalación

Para trabajar con el proyecto se recomienda disponer de las siguientes herramientas:

- **Lenguaje de programación:** C++.
- **Compilador:** GCC (`g++`), mediante una instalación compatible como MSYS2.
- **Entorno de desarrollo:** Visual Studio Code.
- **Control de versiones:** Git.
- **Repositorios remotos:** GitHub y GitLab.
- **Documentación:** Markdown y PDF.
- **Alternativa de compilación:** OnlineGDB, cuando no sea posible compilar localmente.

### Instalación

1. Instalar Git y un compilador de C++ compatible con GCC, si el equipo lo permite.
2. Instalar Visual Studio Code, si todavía no está instalado.
3. Clonar el repositorio desde GitHub:

   ```bash
   git clone URL_DEL_REPOSITORIO
   ```

4. Ingresar en la carpeta del proyecto:

   ```bash
   cd repasogeneral
   ```

5. Abrir el proyecto en Visual Studio Code:

   ```bash
   code .
   ```

**Nota:** reemplazar `URL_DEL_REPOSITORIO` por la dirección real del repositorio.

Si las computadoras disponibles no permiten instalar o ejecutar el compilador, se puede utilizar OnlineGDB y guardar las capturas correspondientes como evidencia.

## Ejecución

El archivo principal del programa se encuentra en `src/main.cpp`. Contiene los tres retos de la actividad.

### 1. Compilar

Desde la terminal PowerShell de Visual Studio Code, ubicada en la carpeta raíz del proyecto, ejecutar:

```powershell
g++ src/main.cpp -o src/repasogeneral.exe
```

### 2. Ejecutar

```powershell
.\src\repasogeneral.exe
```

La aplicación ejecuta los ejercicios y muestra sus resultados en la consola.

## Menú de Retos

### Reto 1: Recursividad

Implementa la función `sumaRecursiva(int n)`, que calcula la suma de los números enteros desde uno hasta el valor recibido.

El programa utiliza el número `5` como ejemplo y muestra la suma acumulada correspondiente.

Conceptos principales:

- Funciones recursivas.
- Caso base.
- Pila de llamadas (*Stack*).
- Prevención de recursividad infinita.

### Reto 2: Arreglos y búsqueda secuencial

Recorre un arreglo de diez números enteros para localizar el valor `18`.

Cuando encuentra el elemento, muestra su índice y su dirección de memoria. La instrucción `break` interrumpe el ciclo al encontrar la coincidencia.

Conceptos principales:

- Arreglos de tamaño fijo.
- Recorrido mediante índices.
- Búsqueda secuencial.
- Operador de dirección (`&`).
- Complejidad temporal \(O(n)\).

### Reto 3: Intercambio de valores con punteros

Utiliza la función `intercambiarValores(int* ptrA, int* ptrB)` para intercambiar los valores de dos variables enteras.

El ejemplo inicial utiliza los valores `100` y `500`. La función recibe las direcciones de las variables y utiliza una variable temporal para completar el intercambio.

Conceptos principales:

- Declaración y utilización de punteros.
- Pasaje por dirección.
- Operador de desreferenciación (`*`).
- Modificación de las variables originales.
- Uso de una variable temporal.

## Estructura Obligatoria del Repositorio

La carpeta raíz `repasogeneral` debe organizarse de la siguiente manera:

```text
repasogeneral/
├── .gitignore
├── LICENSE
├── README.md
├── docs/
│   ├── InformeEEST1_LPR2026_ACT06_G03_Informe_v1.0.0.pdf
│   ├── CHANGELOG.md
│   └── manuales/
│       ├── manual_programador_v1.0.0.pdf
│       └── manual_usuario_v1.0.0.pdf
├── src/
│   └── main.cpp
└── capturas/
    ├── ejecucion_repasogeneral.png
    └── traza_memoria.png
```

### Descripción de los directorios y archivos

- **`.gitignore`:** excluye archivos ejecutables, archivos temporales y configuraciones locales que no deben incluirse en el repositorio.
- **`LICENSE`:** contiene los términos de la licencia MIT de uso escolar.
- **`README.md`:** presenta la información general, los requisitos, las instrucciones y los retos de la actividad.
- **`docs/`:** almacena el informe académico y el registro de modificaciones.
- **`docs/CHANGELOG.md`:** registra los cambios y las versiones del proyecto.
- **`docs/manuales/`:** contiene los manuales del programador y del usuario en formato PDF.
- **`src/`:** contiene el código fuente del programa.
- **`src/main.cpp`:** reúne los tres retos del taller en una única aplicación.
- **`capturas/`:** almacena las evidencias gráficas de ejecución y el esquema de memoria.

Los nombres de los archivos deben coincidir con los utilizados en el repositorio real. El informe debe elaborarse según las normas APA 7, de acuerdo con las indicaciones de la actividad.

## Documentación y Evidencias

El proyecto debe incluir los siguientes entregables:

- **Informe académico:** `docs/InformeEEST1_LPR2026_ACT06_G03_Informe_v1.0.0.pdf`.
- **Manual del programador:** `docs/manuales/manual_programador_v1.0.0.pdf`.
- **Manual del usuario:** `docs/manuales/manual_usuario_v1.0.0.pdf`.
- **Registro de cambios:** `docs/CHANGELOG.md`.
- **Captura de ejecución:** `capturas/ejecucion_repasogeneral.png`.
- **Traza de memoria:** `capturas/traza_memoria.png`.

El informe debe incluir las respuestas justificadas al cuestionario técnico de cinco preguntas, además de los nombres y las tareas específicas de cada integrante si se presenta como trabajo grupal.

Las capturas deben servir como evidencia de la ejecución y del proceso de desarrollo. También se debe documentar la configuración de Git cuando se implemente la estrategia de doble destino.

## Control de Versiones: GitHub y GitLab

El proyecto utiliza Git para registrar los cambios realizados en el código y la documentación. La actividad propone configurar dos destinos de publicación para conservar una copia del repositorio tanto en GitHub como en GitLab.

### Configuración de los repositorios remotos

Primero, crear un repositorio vacío en GitLab con el mismo nombre que el repositorio de GitHub.

Desde la terminal, configurar la URL principal y los dos destinos de publicación:

```bash
git remote set-url origin https://github.com/tu-usuario/repasogeneral.git
git remote set-url --add --push origin https://github.com/tu-usuario/repasogeneral.git
git remote set-url --add --push origin https://gitlab.com/tu-usuario/repasogeneral.git
```

Reemplazar `tu-usuario` por el nombre de usuario correspondiente en cada plataforma.

### Verificar la configuración

Ejecutar:

```bash
git remote -v
```

La configuración debe mostrar una dirección de lectura (*fetch*) y dos destinos de publicación (*push*): uno para GitHub y otro para GitLab.

### Publicar los cambios

```bash
git branch -M main
git add .
git commit -m "feat: completar taller de repaso en C++"
git push -u origin main
```

Una vez configurados correctamente ambos destinos, los siguientes `git push` pueden utilizarse para publicar los cambios en los dos repositorios.

## Objetivos de la Actividad

- Consolidar los conocimientos sobre recursividad y casos base.
- Comprender el funcionamiento de la pila de llamadas.
- Implementar una búsqueda secuencial sobre un arreglo.
- Analizar el uso de `break` para interrumpir un recorrido.
- Comprender las direcciones de memoria mediante el operador `&`.
- Intercambiar valores mediante punteros y desreferenciación.
- Compilar, ejecutar y documentar una aplicación de consola en C++.
- Utilizar Git y GitHub para gestionar las versiones del proyecto.
- Configurar GitLab como destino adicional de publicación.
- Mantener actualizados el informe, los manuales, las capturas y el archivo `CHANGELOG.md`.

## Cuestionario Técnico

El informe del proyecto debe responder y justificar las siguientes preguntas:

1. **Caso base:** ¿Qué error crítico puede producirse si una función recursiva carece de una condición de corte?
2. **Eficiencia:** ¿Por qué la instrucción `break` puede mejorar el rendimiento de una búsqueda secuencial?
3. **Direccionamiento:** ¿Cómo se puede comprobar mediante el operador `&` que los elementos de un arreglo ocupan posiciones de memoria consecutivas?
4. **Variables temporales:** ¿Qué función cumple la variable temporal en el intercambio de valores con punteros?
5. **Autoevaluación:** ¿Cuál de los tres retos resultó más complejo de comprender y cómo se resolvió?

## Licencia

Este proyecto se distribuye bajo la licencia MIT de uso escolar. Consultar el archivo `LICENSE`, ubicado en la raíz del repositorio, para conocer las condiciones de uso, modificación y distribución.

---

**REPASOGENERAL — Actividad 6: Taller Práctico de Repaso y Consolidación en C++**  
Proyecto Integrador Anual · Laboratorio de Programación · EEST N.º 1 “Eduardo Ader” · 2026
