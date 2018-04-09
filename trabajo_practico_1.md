Introduccion

    ¿Qué es una aplicación? Una aplicación es un programa informático diseñado como herramienta para permitir a un usuario realizar uno o diversos tipos de tareas. Las aplicaciones pertenecen al software de aplicación.

    ¿Qué es un algoritmo? un algoritmo es un conjunto prescrito de instrucciones o reglas bien definidas, ordenadas y finitas que permite llevar a cabo una actividad mediante pasos sucesivos que no generen dudas a quien deba hacer dicha actividad. Dados un estado inicial y una entrada, siguiendo los pasos sucesivos se llega a un estado final y se obtiene una solución. Los algoritmos son el objeto de estudio de la algoritmia.

    ¿A que se refiere el concepto de lenguaje de alto nivel? Se caracteriza por expresar los algoritmos de una manera adecuada a la capacidad cognitiva humana, en lugar de la capacidad que se la ejecuta de las máquinas.

Los lenguajes de alto nivel se crearon para que el usuario común pudiese solucionar un problema de procesamiento de datos de una manera más fácil y rápida.

Ventajas

Genera un código más sencillo y comprensible.
Escribir un código válido para diversas máquinas o sistemas operativos.
Permite utilizar paradigmas de programación.
Permite crear programas complejos en relativamente menos líneas de código.

Inconvenientes

Reducción de velocidad al ceder el trabajo de bajo nivel a la máquina.
Algunos requieren que la máquina cliente posea una determinada plataforma.

ej de lenguaje de alto nivel:basic,java,python,ruby

    Teniendo en cuenta lo visto anteriormente. ¿Qué es un S.O? Es el software principal o conjunto de programas de un sistema informático que gestiona los recursos de hardware y provee servicios a los programas de aplicación de software, ejecutándose en modo privilegiado respecto de los restantes (aunque puede que parte de él se ejecute en espacio de usuario).

    ¿A qué nos referimos cuando hablamos de la arquitectura de una computadora? Es el diseño conceptual y la estructura operacional fundamental de un sistema de computadoras. Es decir, es un modelo y una descripción funcional de los requerimientos y las implementaciones de diseño para varias partes de una computadora, con especial interés en la forma en que la unidad central de proceso (CPU) trabaja internamente y accede a las direcciones de memoria.

También suele definirse como la forma de interconectar componentes de hardware, para crear computadoras según los requerimientos de funcionalidad, rendimiento y costo.

La computadora recibe y envía la información a través de los periféricos, por medio de los canales. La CPU es la encargada de procesar la información que le llega a la computadora. El intercambio de información se tiene que hacer con los periféricos y la CPU.

    Describa y grafique los elementos de la Arquitectura de Von Neumann. Es una arquitectura de computadoras basada en la descrita en 1945 por el matemático y físico John von Neumann y otros, en el primer borrador de un informe sobre el EDVAC. Este describe una arquitectura de diseño para un computador digital electrónico con partes que constan de una unidad de procesamiento que contiene una unidad aritmético lógica y registros del procesador, una unidad de control que contiene un registro de instrucciones y un contador de programa, una memoria para almacenar tanto datos como instrucciones, almacenamiento masivo externo, y mecanismos de entrada y salida. El concepto ha evolucionado para convertirse en un computador de programa almacenado en el cual no pueden darse simultáneamente una búsqueda de instrucciones y una operación de datos, ya que comparten un bus en común. Esto se conoce como el cuello de botella Von Neumann, y muchas veces limita el rendimiento del sistema

Organización del cpu:

¿Cómo está compuesta una CPU? CPU esta compuesta por la memoria principal, la unidad aritmético-lógica y la unidad o procesador de control.

¿Qué son los flags?Enumere y explique cada uno. El campo Flags en un protocolo de comunicaciones TCP utiliza 6 bits para activar o desactivar cada una de las siguientes funciones:

    URG: Especifica a la máquina receptora la existencia de información urgente en el flujo de datos. ACK: Se corresponde con una respuesta de correcta recepción de un paquete anterior que se envió a otra máquina. PSH: Indica a la máquina receptora que debe pasar la información a la capa de aplicación (programas) lo más rápido posible. Flag RST: Especifica el reinicio de la conexión entre la máquina receptora y la emisora. SYN: Se utiliza para la sincronización de números de secuencia entre máquinas. FIN: Indica que debe empezar el proceso de fin de conexión.

Realice un gráfico con todos los elementos de la CPU.

    Unidad de Control (UC): obtiene instrucciones desde la memoria y las "ejecuta" dirigiendo operaciones coordinadas con la UAL, registros y otros componentes.

    Unidad aritmético-lógica (UAL o ALU en inglés): realiza operaciones aritméticas y lógicas.

    Registros de procesador: proveen operandos al UAL y almacenan los resultados obtenidos en el UAL

Los procesadores vectoriales tienen múltiples procesadores que operan en paralelo, no tiene una unidad considerada central.

¿Qué es y para qué sirve un registro? 
Un registro es una memoria de alta velocidad y poca capacidad, integrada en el microprocesador, que permite guardar transitoriamente y acceder a valores muy usados, generalmente en operaciones matemáticas.

Los registros están en la cumbre de la jerarquía de memoria, y son la manera más rápida que tiene el sistema de almacenar datos. Los registros se miden generalmente por el número de bits que almacenan; por ejemplo, un "registro de 8 bits" o un "registro de 32 bits". 

instrucciones

¿Qué es una instrucción? Describa su composición y para qué sirve.

Markdown
Toggle Zen Mode
Preview
Toggle Mode

Una instrucción es un conjunto de símbolos(que usualmente son caracteres) que representan una orden de operación o tratamiento de información para la computadora. Las instrucciones suelen realizarse con datos o actuar sobre estos. Un programa es un conjunto ordenado e instrucciones que se suministran al ordenador y le indican la tarea a realizar.

Las instrucciones se forman con elementos o símbolos de un repertorio determinado y se construyen siguiendo unas reglas precisas. Al conjunto de símbolos y reglas sintácticas con las que se redactan los programas, se le denomina lenguaje de programación. Los circuitos de la computadora solo pueden leer instrucciones formadas por bits 0 y 1, que conforman un conocido lenguaje llamado maquina. Estos bits están agrupados en bloques o campos. En todas las instrucciones maquina existe un bloque que contiene el código de operación(un conjunto de bits que identifican la operación a realizar), y en la mayoría de ellas existe un bloque de dirección que contiene información para acceder al dato sobre el que actúa el bloque de operación.

Las instrucciones se pueden clasificar en los siguientes grupos:

    De transferencia de datos de E/S.

    De calculo o tratamiento(aritmético-lógicas).

    De bifurcación o ruptura de frecuencia, que permiten alterar el orden de ejecución de las sentencias.

    De control.
    
operadores:

 direcciones:
    
    Con dos operandos. Al código de operación le siguen dos operaciones de memoria que apuntan a las posiciones que contienen los datos que van a intervenir en la operación actuando una de ellas como receptora del resultado de la operación.

    Con un operando. Se utiliza generalmente en computadoras cuya arquitectura funciona con filosofía de acumulador (Ej: ODE), al código de operación le sigue la dirección de uno de los operandos, en el acumulador se deposita el resultado de la operación.

    Sin operandos. Se utilizan con arquitecturas con filosofía de pila, el sistema mantiene una serie de punteros para la gestión de la pila y tanto un operando como el otro se extraen de la pila y el resultado se vuelve a guardar en la pila.



Métodos de direccionamiento:

Es el modo que utiliza una instrucción para indicar la posición de memoria del dato o los datos que van a intervenir en la misma. Normalmente en una instrucción maquina se suelen utilizar algunos de los siguientes métodos de direccionamiento:

    Direccionamiento inmediato: En este método el dato que interviene en la instrucción forma parte de la propia instrucción no necesita por tanto ningún acceso a memoria para acceder al dato.

    Direccionamiento directo: Con el código de operación se especifica la dirección de la posición de memoria que va a intervenir en dicha operación, se necesita un acceso a memoria para trasladar el dato desde la memoria interna hasta el bloque de operaciones(Ej: ODE).

    Direccionamiento indirecto: Con el código de operación se especifica la dirección de la posición de memoria que contiene la dirección del dato, a esta dirección se le denomina dirección intermedia, para acceder al dato se necesita al menos 2 accesos a la memoria interna, pero este modo permite direccionar un mayor número de posiciones de memoria, porque utiliza todos los bits de la palabra para codificar la dirección.

    Direccionamiento relativo: Con el código de operación se especifica la posición en la memoria a partir de una dirección base que se haya almacenada en un registro especial. De esta manera se posibilita el acceso a un conjunto de posiciones consecutivas a partir de esta dirección base.

Describa el ciclo de instrucciones.

Buscar la instrucción en la memoria principal:

Se vuelca el valor del contador de programa sobre el bus de direcciones. Entonces la CPU pasa la instrucción de la memoria principal a través del bus de datos al Registro de Dirección de Memoria (MAR). A continuación el valor del MAR es colocado en el Registro de Instrucción Actual (CIR), un circuito que guarda la instrucción temporalmente de manera que pueda ser decodificada y ejecutada.

Decodificar la instrucción:

El decodificador de instrucción interpreta e implementa la instrucción. El registro de instrucción (IR) mantiene la instrucción en curso mientras el contador de programa (PC, program counter) guarda la dirección de memoria de la siguiente instrucción a ser ejecutada.

    Recogida de datos desde la memoria principal
    Se accede al banco de registros por los operandos (solo si es necesario)
    Se calcula el valor del operando inmediato con extensión de signo (solo si es necesario)

También se lee la dirección efectiva de la memoria principal si la instrucción tiene una dirección indirecta, y se recogen los datos requeridos de la memoria principal para ser procesados y colocados en los registros de datos.

Ejecutar la instrucción:

A partir del registro de instrucción, los datos que forman la instrucción son decodificados por la unidad de control. Ésta interpreta la información como una secuencia de señales de control que son enviadas a las unidades funcionales relevantes de la CPU para realizar la operación requerida por la instrucción poder terminarla y seguir asi.

Almacenar o guardar resultados:

El resultado generado por la operación es almacenado en la memoria principal o enviado a un dispositivo de salida dependiendo de la instrucción. Basándose en los resultados de la operación, el contador de programa se incrementa para apuntar a la siguiente instrucción o se actualiza con una dirección diferente donde la próxima instrucción será recogida.

Buses:
¿Que es un bus y que función cumple? Enumere y explique los tipos que existen.

Es un sistema digital que transfiere datos entre los componentes de una computadora o entre varias computadoras. Está formado por cables o pistas en un circuito impreso, dispositivos como resistores y condensadores además de circuitos integrados.

tipos de buses:

Bus paralelo: Es un bus en el cual los datos son enviados por bytes al mismo tiempo, con la ayuda de varias líneas que tienen funciones fijas. La cantidad de datos enviada es bastante grande con una frecuencia moderada y es igual al ancho de los datos por la frecuencia de funcionamiento. En los computadores ha sido usado de manera intensiva, desde el bus del procesador, los buses de discos duros, tarjetas de expansión y de vídeo, hasta las impresoras.

El front-side bus de los procesadores Intel es un bus de este tipo y como cualquier bus presenta unas funciones en líneas dedicadas:

    Las líneas de dirección son las encargadas de indicar la posición de memoria o el dispositivo con el que se desea establecer comunicación.
    Las líneas de control son las encargadas de enviar señales de arbitraje entre los dispositivos. Entre las más importantes están las líneas de interrupción, DMA y los indicadores de estado.
    Las líneas de datos transmiten los bits de forma aleatoria de manera que por lo general un bus tiene un ancho que es potencia de 2.

Un bus paralelo tiene conexiones físicas complejas, pero la lógica es sencilla, que lo hace útil en sistemas con poco poder de cómputo. En los primeros microcomputadores, el bus era simplemente la extensión del bus del procesador y los demás integrados "escuchan" las línea de direcciones, en espera de recibir instrucciones. En el PC IBM original, el diseño del bus fue determinante a la hora de elegir un procesador con I/O de 8 bits (Intel 8088), sobre uno de 16 (el 8086), porque era posible usar hardware diseñado para otros procesadores, abaratando el producto.

Bus serie:En este los datos son enviados, bit a bit y se reconstruyen por medio de registros o rutinas. Está formado por pocos conductores y su ancho de banda depende de la frecuencia. Aunque originalmente fueron usados para conectar dispositivos lentos (como el teclado o un ratón), actualmente se están usando para conectar dispositivos mucho más rápidos como discos duros, unidades de estado sólido, tarjetas de expansión e incluso para el bus del procesador.

Bus de control: El bus de control gobierna el uso y acceso a las líneas de datos y de direcciones. Como éstas líneas están compartidas por todos los componentes, tiene que proveerse de determinados mecanismos que controlen su utilización. Las señales de control transmiten tanto órdenes como información de temporización entre los módulos. Mejor dicho, es el que permite que no haya colisión de información en el sistema.

Bus de direcciones:La memoria RAM es direccionable, de forma que cada celda de memoria tiene su propia dirección. Las direcciones son un número que selecciona una celda de memoria dentro de la memoria principal o en el espacio de direcciones de la unidad de entrada/salida.

El bus de direcciones es un canal del microprocesador totalmente independiente del bus de datos donde se establece la dirección de memoria del dato en tránsito.

El bus de dirección consiste en el conjunto de líneas eléctricas necesarias para establecer una dirección. La capacidad de la memoria que se puede direccionar depende de la cantidad de bits que conforman el bus de direcciones, siendo 2n el tamaño máximo en bits del banco de memoria que se podrá direccionar con n líneas. Por ejemplo, para direccionar una memoria de 256 bits, son necesarias al menos 8 líneas, pues 28 = 256. Adicionalmente pueden ser necesarias líneas de control para señalar cuándo la dirección está disponible en el bus. Esto depende del diseño del propio bus.

Bus de datos: El bus de datos permite el intercambio de datos entre la CPU y el resto de unidades.

¿Que ventaja tiene un bus frente a otro si es más ancho?

VIM:

¿Qué es VIM?¿Para qué sirve? ¿Se considera buena herramienta?

Vim, como su antecesor vi, se utiliza desde un terminal en modo texto. Se controla por completo mediante el teclado.

Principales funcionalidades:

Corrector ortográfico integrado
Autocompletado de texto
Navegación por pestañas
Ventanas múltiples, que dividen el área de edición horizontal o verticalmente.
Resaltado de sintaxis dependiente del lenguaje de programación o de etiquetas utilizado
Órdenes deshacer y rehacer
Comprensión de más de 200 sintaxis diferentes
Lenguaje de scripting para programar extensiones
Completado de órdenes, palabras y nombres de ficheros
Compresión y descompresión de ficheros, que posibilita editar ficheros comprimidos
Reconocimiento de formatos de fichero y conversión entre los mismos.
Historial de órdenes ejecutadas
Grabación y reproducción de macros
Guardado de la configuración entre sesiones
Plegado automático y manual de código
Interfaz gráfica opcional
Altamente configurable y personalizable
Casi 100% compatible con vi, pero sin muchos de sus defectos

Utilice VIM para desarrollar algún programa en cualquier lenguaje.

Busque alguna hoja de datos (cheatsheet) de vim y traduzca alguna parte mientras la ejercita.

Realice su propia hoja de datos de vim (ésta tarea le llevará todo el curso). En un documento de Drive o t para subir a Github vaya volcando cualquier conocimiento adquirido en el uso de VIM a medida que lo vaya utilizando.

Busque algún video tutorial de VIM y traslade el conocimiento de al menos 30 minutos de video en una presentación de Google Drive.
[Node.js](https://www.youtube.com/watch?v=WdSIcOiqWmg)
1 [Node.js](https://www.youtube.com/watch?v=ddl8Y0MZHv8)
2 [Node.js](https://www.youtube.com/watch?v=yrlgF1nk1Tc)
3 [Node.js](https://www.youtube.com/watch?v=4QVg4IwOhxM)
4 [Node.js](https://www.youtube.com/watch?v=pOiTtV2myzw)





