# Laboratorio 6: Reconocimiento de partes y funcionamiento de una máquina de anestesia

## Introducción

La anestesia constituye un componente esencial de la atención quirúrgica, pues permite realizar procedimientos diagnósticos y terapéuticos mediante técnicas que controlan la sensibilidad, el dolor, la conciencia y, cuando corresponde, las respuestas fisiológicas del paciente. La elección de la técnica anestésica depende del procedimiento, de las condiciones clínicas y de los objetivos del equipo de salud. En una anestesia general, además de administrar fármacos anestésicos, puede ser necesario asegurar la vía aérea y brindar ventilación asistida o controlada, por lo que el desempeño de los equipos biomédicos adquiere una importancia crítica para la seguridad del paciente [2]–[4].

La **máquina de anestesia** es una estación de trabajo que integra distintos subsistemas para preparar y administrar una mezcla de gases medicinales y, cuando se utiliza anestesia inhalatoria, incorporar concentraciones controladas de agentes anestésicos volátiles. Entre estos subsistemas se encuentran las conexiones a redes y cilindros de gases, los reguladores de presión, los controles de flujo, los vaporizadores, el circuito respiratorio, el ventilador mecánico, los sensores de medición y las alarmas. Su funcionamiento coordinado permite suministrar oxígeno, apoyar el intercambio de gases y supervisar variables respiratorias relevantes durante el procedimiento [1], [5].

Desde el enfoque de la **instrumentación biomédica**, esta máquina no debe entenderse como un único dispositivo, sino como un conjunto de módulos neumáticos, mecánicos, electrónicos y de medición. Por ejemplo, un sistema de regulación de presión acondiciona el gas procedente de la fuente de suministro, mientras que los sensores y circuitos electrónicos contribuyen a monitorizar variables como la presión de la vía aérea, la concentración de oxígeno y los volúmenes ventilatorios. Una alteración en cualquiera de estas etapas —por ejemplo, pérdida de presión en la alimentación, fugas en el circuito, agotamiento del absorbente de dióxido de carbono o errores de configuración del ventilador— puede comprometer el desempeño global del sistema [5].

En esta práctica se estudia la **Mindray WATO EX-20**, una máquina que permite ventilación manual y ventilación mecánica y que, según el manual consultado, dispone de modalidades de ventilación controlada por volumen (VCV) y por presión (PCV). El equipo también incluye opciones de configuración, monitorización, alarmas y mantenimiento. Analizar sus partes permite relacionar conceptos de neumática, control, adquisición de señales, interfaces de usuario y seguridad eléctrica y funcional con un dispositivo utilizado en el entorno quirúrgico [5].

El propósito del laboratorio es reconocer sus componentes y comprender la relación entre suministro de gases, ventilación y vigilancia del funcionamiento. Asimismo, se busca identificar qué elementos del circuito requieren limpieza o desinfección y por qué las pruebas previas al uso, el mantenimiento preventivo y la respuesta adecuada a las alarmas son actividades esenciales. Esta revisión teórica sirve de base para la identificación presencial de partes, la documentación fotográfica y el análisis de fallas en las siguientes etapas de la práctica [1], [5].

## Objetivos

### Objetivo general

Reconocer los componentes, principios de funcionamiento, modos de ventilación y actividades de mantenimiento asociados con la máquina de anestesia **Mindray WATO EX-20**, relacionándolos con su importancia para la seguridad del paciente y la práctica de la ingeniería biomédica [1].

### Objetivos específicos

- Identificar los principales subsistemas de una máquina de anestesia y explicar cómo interactúan durante la administración de gases y el soporte ventilatorio.
- Diferenciar los tipos de anestesia más utilizados en procedimientos quirúrgicos y relacionarlos con el uso de equipos de anestesia.
- Reconocer los gases medicinales empleados, su función y las modalidades de suministro mediante redes centrales o cilindros de alta presión.
- Describir la estructura y función del sistema respiratorio, así como las condiciones generales de reprocesamiento de sus componentes.
- Explicar los menús principales de la interfaz de la WATO EX-20 y los modos de ventilación disponibles, identificando el ajuste de pausa o meseta inspiratoria.
- Valorar la importancia del manual del fabricante, las verificaciones funcionales y el mantenimiento para prevenir fallas y reducir riesgos.

## Parte A

### a) ¿Cuántos y cuáles son los tipos de anestesia que comúnmente se aplican durante una cirugía? Explique cada uno.

Se distinguen **cuatro categorías de atención anestésica**: anestesia general, regional, local y atención anestésica monitorizada, que puede incluir distintos niveles de sedación. Esta clasificación facilita su comparación, aunque **la sedación no constituye necesariamente una técnica independiente de anestesia local o regional**, y la atención anestésica monitorizada (MAC) describe un servicio profesional, no una profundidad fija de sedación [2]–[4].

#### Anestesia general

Es un estado farmacológicamente inducido y reversible en el que el paciente pierde la conciencia y no responde de manera intencional a estímulos dolorosos. Puede lograrse mediante medicamentos intravenosos, anestésicos inhalatorios o una combinación de ambos. Su aplicación requiere vigilancia continua, incluida la evaluación de oxigenación, ventilación y función cardiovascular. Según la intervención y los fármacos empleados, puede ser necesario utilizar dispositivos para asegurar la vía aérea y un ventilador mecánico [2]–[4].

Se utiliza en intervenciones complejas, prolongadas o que exigen inmovilidad y un control preciso de las condiciones operatorias. **Relación con la WATO EX-20:** la estación facilita la administración de gases y agentes inhalatorios y permite apoyar o controlar la ventilación; no administra por sí misma todos los medicamentos utilizados en anestesia general [5].

#### Anestesia regional

Consiste en bloquear temporalmente la conducción de señales nerviosas en una región del cuerpo mediante anestésicos locales administrados cerca de nervios o estructuras del sistema nervioso. Entre sus técnicas se encuentran la **anestesia raquídea o espinal**, la **epidural** y los **bloqueos de nervios periféricos**. La persona puede permanecer consciente o recibir sedación adicional, según las necesidades clínicas [2], [4].

Es frecuente en cirugías de extremidades y en determinados procedimientos obstétricos y abdominales. A diferencia de la anestesia general inhalatoria, la técnica regional no requiere que una máquina de anestesia entregue el fármaco bloqueante; sin embargo, los equipos de oxigenación, monitorización y apoyo respiratorio deben estar disponibles cuando correspondan.

#### Anestesia local

Produce pérdida temporal de sensibilidad en una **zona pequeña y delimitada**, sin inducir por sí sola la pérdida de conciencia. El anestésico puede aplicarse de forma tópica o inyectarse en los tejidos próximos al área de intervención. Se utiliza en suturas, procedimientos dermatológicos, biopsias superficiales y otras intervenciones menores [2], [3].

Generalmente no se necesita una máquina de anestesia para administrar el anestésico local, pues el efecto se obtiene directamente en el área tratada. No obstante, el nivel de monitorización dependerá del procedimiento y de las condiciones del paciente.

#### Sedación y atención anestésica monitorizada

La **sedación** emplea medicamentos para disminuir la ansiedad, la incomodidad y el nivel de alerta. Su profundidad puede ser mínima, moderada o profunda, y puede combinarse con anestesia local o regional. A mayor profundidad, aumenta la posibilidad de requerir intervención para mantener la vía aérea o la ventilación [3], [4].

La **atención anestésica monitorizada (MAC)** supone la evaluación, supervisión y disponibilidad de intervención por parte de un profesional de anestesia durante un procedimiento; puede realizarse con diferentes grados de sedación o incluso sin sedantes. Es habitual en ciertos procedimientos endoscópicos y ambulatorios. No debe equipararse automáticamente con anestesia general ni con una única profundidad de sedación [3].

| Categoría | Conciencia habitual | Área o efecto principal | Ejemplo de aplicación |
|---|---|---|---|
| General | Inconsciencia inducida | Efectos sistémicos | Cirugía abdominal mayor |
| Regional | Despierto o con sedación | Región extensa o territorio nervioso | Cirugía de extremidad, cesárea |
| Local | Generalmente consciente | Área pequeña | Suturas y biopsias superficiales |
| Sedación / MAC | Variable | Disminución de alerta y vigilancia anestésica | Endoscopias y procedimientos ambulatorios |

La WATO EX-20 se relaciona especialmente con procedimientos en los que se administran gases anestésicos y/o se necesita soporte respiratorio. Su uso clínico no define, por sí solo, el tipo de anestesia aplicado [5].

### b) ¿Con cuáles gases trabaja una máquina de anestesia y qué función cumple cada uno? ¿Cuáles de ellos se incorporan a la máquina mediante sistema de alta presión?

Una estación de anestesia maneja **gases medicinales** y puede añadir **vapores de agentes anestésicos inhalatorios**. Es importante diferenciar ambos grupos: los gases medicinales entran desde redes hospitalarias o cilindros y pasan por mecanismos de regulación y control de flujo; los anestésicos volátiles, en cambio, suelen almacenarse como líquidos dentro de vaporizadores compatibles y se incorporan a la corriente de gas fresco en forma de vapor [5].

#### Oxígeno medicinal (O₂)

Es el gas esencial para mantener la oxigenación. La máquina permite regular su flujo y combinarlo con otros gases según el plan anestésico. La proporción inspirada de oxígeno (**FiO₂**) puede monitorizarse mediante el sensor correspondiente. Una pérdida de suministro de oxígeno es una condición crítica, razón por la cual el equipo incorpora mecanismos de advertencia y protecciones relacionadas con el suministro de gases [5].

**Abastecimiento:** Puede ingresar por una **red central de gases medicinales** o por un **cilindro de oxígeno comprimido**, cuya presión debe reducirse antes de incorporarse a los circuitos de control.

#### Óxido nitroso (N₂O)

Es un gas inhalatorio con propiedades analgésicas y anestésicas que puede emplearse como **coadyuvante** en combinación con oxígeno y otros fármacos. No reemplaza al oxígeno ni suele ser suficiente como único anestésico para mantener una anestesia general quirúrgica. Su administración exige controlar la mezcla y disponer de sistemas adecuados para evacuar gases residuales [5].

**Abastecimiento:** Se suministra por red hospitalaria o por un **cilindro presurizado**. En el cilindro puede encontrarse en equilibrio líquido-vapor; por ello, su presión no indica de manera lineal cuánto gas queda disponible. La WATO EX-20 contempla conexiones y verificaciones del suministro de N₂O según su configuración [5].

#### Aire medicinal

Se utiliza como gas portador y permite ajustar la concentración de oxígeno de la mezcla sin introducir N₂O. También puede intervenir en funciones neumáticas del equipo, dependiendo de su configuración. Debe ser aire de **calidad medicinal**, no aire ambiental comprimido sin control de pureza [5].

**Abastecimiento:** Procede de la red central de aire medicinal o, en configuraciones compatibles, de cilindros de aire comprimido.

#### Agentes anestésicos inhalatorios volátiles

Entre los agentes utilizados en anestesia inhalatoria se encuentran **sevoflurano, isoflurano y desflurano**, aunque su disponibilidad y compatibilidad dependen del vaporizador y de la institución. Estos agentes se entregan normalmente en forma líquida al vaporizador específico, donde pasan a la fase de vapor y se mezclan con los gases portadores de manera controlada. Por lo tanto, **no se conectan al sistema de cilindros de gas de alta presión de la misma forma que O₂, N₂O o aire medicinal** [3], [5].

| Sustancia | Papel principal | Origen habitual de suministro | ¿Entra mediante cilindro de alta presión? |
|---|---|---|---|
| Oxígeno (O₂) | Oxigenación del paciente | Red central o cilindro | **Sí**, cuando se usa cilindro |
| Óxido nitroso (N₂O) | Coadyuvante analgésico/anestésico | Red central o cilindro | **Sí**, cuando se usa cilindro |
| Aire medicinal | Gas portador y ajuste de mezcla | Red central o cilindro compatible | **Sí**, si existe suministro por cilindro |
| Sevoflurano, isoflurano, desflurano | Anestesia inhalatoria | Recipiente líquido y vaporizador compatible | **No**, mediante vaporizador |

**Aclaración técnica:** Que una máquina reciba gases presurizados **no significa que todos entren a la misma presión**. La presión elevada se encuentra en la etapa del cilindro; la red hospitalaria trabaja a una presión regulada y la máquina reduce y acondiciona las presiones antes de controlar el flujo hacia el paciente.

### c) ¿Qué es el sistema de respiración en la máquina de anestesia y cuál es su función? ¿Qué partes de este sistema podrían esterilizarse por medio de autoclave?

El **sistema respiratorio** es el conjunto de conductos, válvulas, conexiones, elementos de absorción y medición a través de los cuales circulan los gases hacia el paciente y desde él. En una estación de anestesia con circuito circular, el gas inspirado viaja por una rama inspiratoria y el gas espirado regresa por otra. Las válvulas unidireccionales controlan el sentido de circulación, mientras que un absorbente retira CO₂ del gas espirado para permitir la reutilización de una parte de la mezcla. La máquina puede operar mediante bolsa de ventilación manual o mediante su ventilador mecánico [5].

#### Componentes y función

| Componente | Función dentro del sistema |
|---|---|
| Tubos inspiratorio y espiratorio | Transportar la mezcla gaseosa desde y hacia el paciente |
| Pieza en Y | Conectar las ramas inspiratoria y espiratoria con la interfaz del paciente |
| Válvulas unidireccionales | Favorecer el flujo de gas en el sentido apropiado |
| Recipiente con absorbente de CO₂ | Retener el CO₂ espirado y limitar su reinhalación |
| Bolsa de ventilación manual | Permitir asistencia ventilatoria manual |
| Válvula APL | Limitar y liberar presión excedente en ventilación manual |
| Fuelle y conjunto asociado | Intervenir en la generación o transmisión del movimiento ventilatorio mecánico |
| Sensores de flujo y presión | Medir variables para monitorización y control |
| Sensor de O₂ | Medir la concentración de oxígeno, cuando está instalado |

Desde el punto de vista de la seguridad, las **fugas, conexiones incorrectas, válvulas defectuosas, acumulación de agua y agotamiento del absorbente** pueden alterar el funcionamiento. Por esa razón, el manual indica revisar y probar el sistema después de intervenciones de limpieza o reinstalación [5].

#### Componentes que admiten autoclave

El manual de usuario WATO EX-20, sección **10.3**, establece que las piezas aptas para autoclave están identificadas y que el procedimiento depende del material y de la versión del componente. Su tabla incluye, entre otros, los siguientes elementos [5]:

| Elemento | Posibilidad de autoclave según el manual |
|---|---|
| Tubos respiratorios y pieza en Y | Sí, si son los componentes compatibles especificados |
| Máscara respiratoria reutilizable compatible | Sí |
| Conjunto de válvulas inspiratoria y espiratoria | Sí |
| Recipiente y conexiones del absorbente de CO₂ | Sí, para el conjunto reutilizable especificado, **no para el material absorbente** |
| Componentes del conjunto de fuelle | Sí, con condiciones especiales para el fuelle |
| Recipiente de recolección de condensados y otros componentes indicados | Sí, cuando el modelo y la tabla lo permitan |
| Sensor de flujo convencional | **No**; solo si es la variante identificada como autoclavable |
| Sensor de O₂ | **No** |
| Manómetro de presión de la vía aérea | **No** |
| Tubos de aspiración y botellas recolectoras de líquidos | **No**, según la advertencia del manual |

Para los componentes autorizados, el manual señala una **temperatura máxima de 134 °C**, con tiempos recomendados que dependen del componente. Específicamente, para el **fuelle** indica **121 °C durante 20 minutos** o **134 °C durante 7 minutos**, mientras que para otros componentes compatibles incluye **134 °C durante 20 minutos**. Estos valores describen el manual consultado: **no deben aplicarse indiscriminadamente a accesorios de reemplazo o de otros fabricantes** [5].

> **Precaución:** No se debe esterilizar el conjunto completo sin desmontarlo ni asumir que todos sus sensores toleran altas temperaturas. Debe verificarse el marcado de cada pieza, el protocolo institucional de reprocesamiento y la versión del manual correspondiente al equipo. El absorbente químico de CO₂ se reemplaza conforme a las instrucciones del fabricante; no se esteriliza para volver a utilizarlo.

### d) ¿Cuántos y cuáles son los submenús del ventilador? ¿En qué consiste cada uno? ¿En cuál de ellos se puede activar la pausa inspiratoria?

En la pantalla principal de la **WATO EX-20**, el manual consultado describe **cuatro opciones principales de menú** asociadas con la gestión del equipo. Es importante distinguir estos menús de los **dos modos de ventilación mecánica** VCV y PCV, pues la pregunta puede interpretarse de ambas maneras. A continuación se presentan ambos conceptos [5].

#### Cuatro opciones principales de la interfaz

| Opción de menú | ¿Para qué sirve? |
|---|---|
| **Modo de ventilación** | Permite seleccionar el modo de ventilación mecánica y acceder a su configuración. |
| **Configuración de alarmas** | Permite ajustar límites y opciones de alarma del ventilador y, si está instalado, del módulo de gases. |
| **Configuración de usuario**  | Agrupa ajustes de monitorización, presentación en pantalla, sonido y otros parámetros de configuración. |
| **Mantenimiento** | Da acceso a funciones relacionadas con verificaciones, pruebas de fugas, calibraciones y ajustes técnicos, según permisos y configuración. |

#### Modos de ventilación: VCV y PCV

**VCV — Ventilación controlada por volumen.** El operador selecciona el volumen corriente objetivo (VC), la frecuencia respiratoria y la relación entre los tiempos inspiratorio y espiratorio (I:E). La máquina busca administrar el volumen configurado, mientras la presión requerida depende de la mecánica respiratoria y de los límites de seguridad. Entre los parámetros de este modo están `VC`, `Frecuencia`, `I:E`, `TIP:TI`, `Plimit` y `PEEP` [5].

**PCV — Ventilación controlada por presión.** El operador selecciona la presión inspiratoria objetivo (`Pinsp`), la frecuencia, la relación `I:E`, el tiempo de ascenso de presión (`Tslope`) y la `PEEP`. En este caso, el volumen corriente resultante **no se fija directamente**: cambia según la resistencia, la distensibilidad y las condiciones del circuito y del paciente [5].

| Característica | VCV | PCV |
|---|---|---|
| Variable objetivo principal | Volumen corriente (VC) | Presión inspiratoria (Pinsp) |
| Variable que puede variar con la mecánica respiratoria | Presión inspiratoria | Volumen corriente |
| Parámetros característicos | VC, frecuencia, I:E, TIP:TI, Plimit, PEEP | Pinsp, frecuencia, I:E, Tslope, PEEP |
| Opción explícita `TIP:TI` | **Sí** | No aparece entre los ajustes indicados para PCV en este manual |

#### ¿Dónde se activa la pausa inspiratoria?

La **pausa o meseta inspiratoria programada** se configura en **VCV** mediante el parámetro **`TIP:TI`**, que representa la proporción del tiempo inspiratorio destinada a la meseta o pausa de flujo. Una vez suministrado el volumen correspondiente, esta fase contribuye a disponer de un intervalo durante el cual el flujo inspiratorio se reduce o se interrumpe, según el funcionamiento de la modalidad [5].

El manual documenta el ajuste `TIP:TI` como **desactivado o ajustable entre 5 % y 60 %**, en incrementos del **5 %**, dependiendo de la configuración. Esto no debe confundirse con mantener presionada una función de pausa manual ni con la medición aislada de presión meseta en otros equipos [5].

