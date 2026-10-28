# A1.1 - Relacion software-hardware con Tinkercad

Completa esta plantilla en tu repositorio individual creado al aceptar el
assignment de Classroom 50.

## Identificacion

- **Nombre y apellidos:** [Tu nombre y apellidos]
- **Modulo:** Entornos de desarrollo (EDES)
- **Unidad:** U1 - Introduccion al desarrollo de software
- **Practica:** A1.1 - Relacion software-hardware con Tinkercad
- **Fecha:** [AAAA-MM-DD]

## Enunciado y recursos

- **Enunciado:** https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica004/
- **Circuito de Tinkercad:** [Enlace al circuito utilizado]

## 1. Registro de pulsaciones

Completa la tabla con los valores observados en la simulacion.

| Accion | Lectura del boton | `estadoLED` despues de la accion | LED observado |
|---|---|---|---|
| Inicio, sin pulsar | [LOW/HIGH] | [0/1] | [Apagado/encendido] |
| Primera pulsacion | [LOW/HIGH] | [0/1] | [Apagado/encendido] |
| Segunda pulsacion | [LOW/HIGH] | [0/1] | [Apagado/encendido] |
| Tercera pulsacion | [LOW/HIGH] | [0/1] | [Apagado/encendido] |

## 2. Respuestas

### 1.a. Ejecucion en el procesador

#### 1.a.1. Fases de una instruccion

[Explica las fases de busqueda, decodificacion y ejecucion.]

#### 1.a.2. Relacion con el programa

[Relaciona esas fases con la lectura del boton, la condicion, el cambio de
estado y la escritura en el LED.]

#### 1.a.3. Observacion en Tinkercad

[Indica que fases internas puedes observar directamente y cuales solo puedes
explicar a partir del modelo.]

### 1.b. Memoria y estado de los componentes

#### 1.b.1. Variables de estado

[Explica que conservan `estadoBoton`, `estadoAnteriorBoton` y `estadoLED`.]

#### 1.b.2. Programa en Arduino Uno

[Indica donde se almacena normalmente el programa compilado.]

#### 1.b.3. Variables durante la ejecucion

[Indica donde se mantienen normalmente las variables globales.]

#### 1.b.4. Boton y memoria

[Explica si el boton escribe directamente en la RAM o si el microcontrolador
lee primero la senal del pin.]

### 1.c. Comunicacion con los perifericos

#### 1.c.1. Senal del boton

[Explica como llega la senal del boton al microcontrolador.]

#### 1.c.2. Orden para el LED

[Explica como llega al LED la orden de encendido o apagado.]

#### 1.c.3. Pines y funciones

[Identifica los pines 7 y 13 y las funciones que leen y escriben en ellos.]

#### 1.c.4. Sondeo o interrupciones

[Indica si el programa utiliza interrupciones o consulta el boton desde
`loop()`.]

### 1.d. Interaccion entre procesador, memoria y perifericos

[Describe, en orden, que ocurre desde que pulsas el boton hasta que cambia el
LED. Distingue hardware y software.]

### 1.e. Cambios en los datos durante la ejecucion

#### 1.e.1. Variables

[Explica como se actualizan las variables de estado.]

#### 1.e.2. Reinicio o apagado

[Explica que ocurre con esos datos al reiniciar o apagar la placa.]

#### 1.e.3. Informacion no visible

[Indica que informacion interna no muestra directamente la simulacion.]

### 1.f. Funcion de las instrucciones del software

#### 1.f.1. Lectura de entrada

[Identifica las sentencias o funciones que leen la entrada.]

#### 1.f.2. Deteccion de una pulsacion

[Identifica la parte que detecta una pulsacion nueva.]

#### 1.f.3. Decision del estado del LED

[Identifica la sentencia que decide el siguiente estado logico.]

#### 1.f.4. Control de la salida

[Identifica la sentencia que controla el LED.]

#### 1.f.5. Compilacion

[Explica como el compilador transforma el programa para que el procesador
pueda ejecutar las operaciones y relacionarse con el hardware.]

### 1.g. Simulacion y ordenador real

[Explica que relacion entre procesador, memoria, programa y entrada/salida
representa la actividad. Distingue los aspectos comunes y las simplificaciones
de Arduino y Tinkercad.]

## 3. Evidencias

Inserta una captura donde se vea el circuito funcionando:

![Circuito en funcionamiento](ruta/a/la/captura.png)

Si no pudiste utilizar el circuito compartido, explica la incidencia y muestra
una captura de tu propio montaje.

## 4. Reflexion final

[Resume como colaboran el software, el procesador, la memoria y los perifericos
en esta actividad.]

## 5. Comprobacion de la entrega

- [ ] El circuito lee LOW en reposo y HIGH al pulsar.
- [ ] Cada pulsacion completa cambia una vez el estado del LED.
- [ ] La tabla recoge al menos tres pulsaciones.
- [ ] Las siete preguntas estan respondidas con tus palabras.
- [ ] La captura permite comprobar la simulacion.
- [ ] La reflexion final relaciona software, procesador, memoria y perifericos.
- [ ] El README no conserva instrucciones sin completar ni marcadores como
  `[Tu nombre y apellidos]`.
