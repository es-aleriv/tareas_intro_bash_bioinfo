##Mi equipo | Alejandra Rivera

1) Identificación del equipo
- Marca y modelo: Apple MacBook Air.
- Tipo: Laptop.

2) Sistema operativo
- Sistema operativo: macOS.
- Versión exacta: macOS Sequoia 15.x.
- Arquitectura del sistema: ARM64 (Apple Silicon).

3) CPU 
- Modelo exacto: Apple M4.
- Núcleos/Threads: 10 núcleos (4 de alto rendimiento y 6 de eficiencia).
- Frecuencia base/turbo: no especificado.
    
4) Memoria RAM
- RAM instalada: 24 GB.
- Tipo y velocidad: Memoria unificada LPDDR5X (soldada al chip). No se especifica la velocidad.
- Capacidad máxima: 24 GB.

5) Almacenamiento
- Tipo: SSD (integrado).
- Capacidad total: Mi SSD es de 512 GB (así me la vendieron), pero el sistema me muestra 494.38 GB reales utilizables.
- ¿Se puede agregar o cambiar por un SSD o NVMe? No, el almacenamiento está soldado.

6) Modelo de procesamiento gráfico (GPU)
- Tipo: Integrados 
- Modelo: GPU integrada en el chip Apple M4.  


#Reflexión final
En mi computadora, la principal limitante para bioinformática no es el CPU, ya que el chip Apple M4 cuenta con 10 núcleos y ofrece un rendimiento bastante eficiente para análisis que utilizan múltiples threads. Tampoco el GPU representa una limitación importante, debido a que la mayoría de los programas de bioinformática que utilizo no están optimizados su uso.

La limitante más importante, desde mi perspectiva, podría ser la RAM, especialmente si trabajara con ensambles genómicos, búsquedas de homología contra bases de datos de muchos gigabytes (como la base de datos de proteínas no redundantes de NCBI) o ensambles de novo. Este tipo de análisis puede requerir grandes cantidades de memoria para ejecutarse de manera eficiente. Además, al tratarse de una MacBook Air sin ventilador, el factor térmico definitivamente podría influir en el rendimiento durante análisis prolongados, afectando los tiempos de ejecución.

No obstante, afortunadamente tengo acceso al servidor del Instituto de Ecología, donde ejecuto los análisis más demandantes en términos de recursos computacionales. En ese contexto, utilizo mi equipo principalmente para tareas menos exigentes, como lectura y redacción, gestión de correos electrónicos y ejecución de análisis rápidos en bash (por ejemplo, extracción de ORFs o scaffolds de conjuntos genómicos, así como el procesamiento y organización de información dentro de bases de datos).
En caso de no trabajar directamente con ese servidor, también tengo otras alternativas en línea como Galaxy, que permite realizar ensambles genómicos, búsquedas de homología para la predicción de CDS y la identificación de ORFs (marcos de lectura abiertos), así como análisis de completitud genómica, entre otros. Asimismo, puedo realizar búsquedas de homología mediante BLAST en línea (ya sea con secuencias de proteínas o nucleótidos), aunque este proceso puede resultar más laborioso, dado que los resultados suelen obtenerse de manera individual. Otra opción a la que tengo acceso es el uso del software bioinformático Geneious en la computadora de la oficina de mi tutora, donde también se pueden predecir ORFs, realizar alineamientos, mapear genomas, entre otros análisis. En algunos casos, estos recursos en línea pueden hacer uso de GPU, RAM y CPU en sus propios servidores, aunque ello no depende directamente de mi equipo.
Sin embargo, en la práctica, la mayor parte de mi análisis los realizo en el servidor del Instituto de Ecología, incluyendo el procesamiento de datos mediante scripts en Python, ya que es más eficiente, permite automatizar procesos, reduce considerablemente los tiempos de ejecución y facilita el manejo de grandes volúmenes de datos. Además ya estoy muy familiarizada con su entorno de trabajo, lo que me permite optimizar mi flujo de análisis. 

En conclusión, evito utilizar mi equipo para procesos bioinformáticos intensivos, ya que prefiero mantenerlo disponible y ágil para las tareas que realizo localmente. Aunque, si tuviera que emplearlo para análisis más demandantes, la RAM y el rendimiento en ejecuciones prolongadas o con bases de datos grandes serían las principales limitantes, más que el CPU o la unidad de procesamiento gráfico (GPU).
