## **Actividad de Investigación: Anatomía de la Compilación en Java y C#**

### **Objetivo de la Actividad** 🎯

Comprender y analizar en profundidad el proceso de compilación y ejecución de los lenguajes de programación Java y C#, identificando las similitudes y diferencias clave que explican su rendimiento y su capacidad multiplataforma.

### **Descripción**

En esta actividad, realizarás una investigación comparativa sobre cómo un programa escrito en Java y otro en C# se transforman desde el código fuente que escribes hasta convertirse en una aplicación funcional. Deberás explorar los componentes clave como compiladores, código intermedio y máquinas virtuales.

### **Tareas a Realizar** 💻

1.  **Del Código Fuente al Ejecutable:**
    * Investiga y crea un diagrama de flujo o un esquema detallado que ilustre, paso a paso, el proceso completo para cada lenguaje:
        * **Java:** Desde el archivo `.java` hasta la ejecución por la Máquina Virtual de Java (JVM). Identifica qué es el **Bytecode**.
        * **C#:** Desde el archivo `.cs` hasta su ejecución por el Common Language Runtime (CLR). Identifica qué es el **Common Intermediate Language (CIL)**.
    * Describe brevemente la función de cada elemento en tus diagramas (ej. compilador `javac`, JIT compiler, CLR, etc.).

2.  **Análisis del Rendimiento en el Primer Arranque:**
    * Investiga el concepto de **Compilación Just-In-Time (JIT)**.
    * Explica razonadamente por qué una aplicación desarrollada en C# (y también en Java) puede ser ligeramente más lenta la *primera vez* que se ejecuta en comparación con ejecuciones posteriores. Relaciona tu explicación directamente con el proceso JIT.

3.  **La Magia de la Multiplataforma:**
    * Explica cómo el diseño de la **JVM (Java Virtual Machine)** en Java y el **CLR (Common Language Runtime)** en .NET (para C#) son los responsables de que ambos lenguajes sean considerados multiplataforma.
    * ¿Qué significa la famosa frase de Java: *"Write Once, Run Anywhere"* (Escribe una vez, ejecuta en cualquier lugar)? ¿Se podría aplicar un principio similar a C#? Justifica tu respuesta.

### **Formato de Entrega** 📝

Elabora un informe en formato digital (PDF) que incluya:

* Los diagramas de flujo o esquemas solicitados.
* Las respuestas desarrolladas para cada una de las preguntas de análisis.
* Una conclusión final donde resumas las ventajas y desventajas de estos modelos de compilación híbrida.
* Las fuentes y bibliografía consultadas.
