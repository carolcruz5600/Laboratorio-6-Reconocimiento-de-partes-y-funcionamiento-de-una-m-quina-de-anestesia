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

<table align="center">
  <thead>
    <tr>
      <th align="center">Categoría</th>
      <th align="center">Conciencia habitual</th>
      <th align="center">Área o efecto principal</th>
      <th align="center">Ejemplo de aplicación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">General</td>
      <td align="center">Inconsciencia inducida</td>
      <td align="center">Efectos sistémicos</td>
      <td align="center">Cirugía abdominal mayor</td>
    </tr>
    <tr>
      <td align="center">Regional</td>
      <td align="center">Despierto o con sedación</td>
      <td align="center">Región extensa o territorio nervioso</td>
      <td align="center">Cirugía de extremidad, cesárea</td>
    </tr>
    <tr>
      <td align="center">Local</td>
      <td align="center">Generalmente consciente</td>
      <td align="center">Área pequeña</td>
      <td align="center">Suturas y biopsias superficiales</td>
    </tr>
    <tr>
      <td align="center">Sedación / MAC</td>
      <td align="center">Variable</td>
      <td align="center">Disminución de alerta y vigilancia anestésica</td>
      <td align="center">Endoscopias y procedimientos ambulatorios</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 1. Comparación de los principales tipos de anestesia utilizados en procedimientos quirúrgicos.</em>
</p>


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


<table align="center">
  <thead>
    <tr>
      <th align="center">Sustancia</th>
      <th align="center">Papel principal</th>
      <th align="center">Origen habitual de suministro</th>
      <th align="center">¿Entra mediante cilindro de alta presión?</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Oxígeno (O₂)</td>
      <td align="center">Oxigenación del paciente</td>
      <td align="center">Red central o cilindro</td>
      <td align="center"><b>Sí</b>, cuando se usa cilindro</td>
    </tr>
    <tr>
      <td align="center">Óxido nitroso (N₂O)</td>
      <td align="center">Coadyuvante analgésico/anestésico</td>
      <td align="center">Red central o cilindro</td>
      <td align="center"><b>Sí</b>, cuando se usa cilindro</td>
    </tr>
    <tr>
      <td align="center">Aire medicinal</td>
      <td align="center">Gas portador y ajuste de mezcla</td>
      <td align="center">Red central o cilindro compatible</td>
      <td align="center"><b>Sí</b>, si existe suministro por cilindro</td>
    </tr>
    <tr>
      <td align="center">Sevoflurano, isoflurano, desflurano</td>
      <td align="center">Anestesia inhalatoria</td>
      <td align="center">Recipiente líquido y vaporizador compatible</td>
      <td align="center"><b>No</b>, mediante vaporizador</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 2. Gases medicinales y agentes anestésicos utilizados en máquinas de anestesia.</em>
</p>


**Aclaración técnica:** Que una máquina reciba gases presurizados **no significa que todos entren a la misma presión**. La presión elevada se encuentra en la etapa del cilindro; la red hospitalaria trabaja a una presión regulada y la máquina reduce y acondiciona las presiones antes de controlar el flujo hacia el paciente.

### c) ¿Qué es el sistema de respiración en la máquina de anestesia y cuál es su función? ¿Qué partes de este sistema podrían esterilizarse por medio de autoclave?

El **sistema respiratorio** es el conjunto de conductos, válvulas, conexiones, elementos de absorción y medición a través de los cuales circulan los gases hacia el paciente y desde él. En una estación de anestesia con circuito circular, el gas inspirado viaja por una rama inspiratoria y el gas espirado regresa por otra. Las válvulas unidireccionales controlan el sentido de circulación, mientras que un absorbente retira CO₂ del gas espirado para permitir la reutilización de una parte de la mezcla. La máquina puede operar mediante bolsa de ventilación manual o mediante su ventilador mecánico [5].

#### Componentes y función


<table align="center">
  <thead>
    <tr>
      <th align="center">Componente</th>
      <th align="center">Función dentro del sistema</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Tubos inspiratorio y espiratorio</td>
      <td align="center">Transportar la mezcla gaseosa desde y hacia el paciente</td>
    </tr>
    <tr>
      <td align="center">Pieza en Y</td>
      <td align="center">Conectar las ramas inspiratoria y espiratoria con la interfaz del paciente</td>
    </tr>
    <tr>
      <td align="center">Válvulas unidireccionales</td>
      <td align="center">Favorecer el flujo de gas en el sentido apropiado</td>
    </tr>
    <tr>
      <td align="center">Recipiente con absorbente de CO₂</td>
      <td align="center">Retener el CO₂ espirado y limitar su reinhalación</td>
    </tr>
    <tr>
      <td align="center">Bolsa de ventilación manual</td>
      <td align="center">Permitir asistencia ventilatoria manual</td>
    </tr>
    <tr>
      <td align="center">Válvula APL</td>
      <td align="center">Limitar y liberar presión excedente en ventilación manual</td>
    </tr>
    <tr>
      <td align="center">Fuelle y conjunto asociado</td>
      <td align="center">Intervenir en la generación o transmisión del movimiento ventilatorio mecánico</td>
    </tr>
    <tr>
      <td align="center">Sensores de flujo y presión</td>
      <td align="center">Medir variables para monitorización y control</td>
    </tr>
    <tr>
      <td align="center">Sensor de O₂</td>
      <td align="center">Medir la concentración de oxígeno, cuando está instalado</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 3. Componentes principales del sistema respiratorio de una máquina de anestesia.</em>
</p>

Desde el punto de vista de la seguridad, las **fugas, conexiones incorrectas, válvulas defectuosas, acumulación de agua y agotamiento del absorbente** pueden alterar el funcionamiento. Por esa razón, el manual indica revisar y probar el sistema después de intervenciones de limpieza o reinstalación [5].

#### Componentes que admiten autoclave

El manual de usuario WATO EX-20, sección **10.3**, establece que las piezas aptas para autoclave están identificadas y que el procedimiento depende del material y de la versión del componente. Su tabla incluye, entre otros, los siguientes elementos [5]:


<table align="center">
  <thead>
    <tr>
      <th align="center">Elemento</th>
      <th align="center">Posibilidad de autoclave según el manual</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Tubos respiratorios y pieza en Y</td>
      <td align="center">Sí, si son los componentes compatibles especificados</td>
    </tr>
    <tr>
      <td align="center">Máscara respiratoria reutilizable compatible</td>
      <td align="center">Sí</td>
    </tr>
    <tr>
      <td align="center">Conjunto de válvulas inspiratoria y espiratoria</td>
      <td align="center">Sí</td>
    </tr>
    <tr>
      <td align="center">Recipiente y conexiones del absorbente de CO₂</td>
      <td align="center">Sí, para el conjunto reutilizable especificado, <strong>no para el material absorbente</strong></td>
    </tr>
    <tr>
      <td align="center">Componentes del conjunto de fuelle</td>
      <td align="center">Sí, con condiciones especiales para el fuelle</td>
    </tr>
    <tr>
      <td align="center">Recipiente de recolección de condensados y otros componentes indicados</td>
      <td align="center">Sí, cuando el modelo y la tabla lo permitan</td>
    </tr>
    <tr>
      <td align="center">Sensor de flujo convencional</td>
      <td align="center"><strong>No</strong>; solo si es la variante identificada como autoclavable</td>
    </tr>
    <tr>
      <td align="center">Sensor de O₂</td>
      <td align="center"><strong>No</strong></td>
    </tr>
    <tr>
      <td align="center">Manómetro de presión de la vía aérea</td>
      <td align="center"><strong>No</strong></td>
    </tr>
    <tr>
      <td align="center">Tubos de aspiración y botellas recolectoras de líquidos</td>
      <td align="center"><strong>No</strong>, según la advertencia del manual</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 4. Compatibilidad de los componentes del sistema respiratorio con la esterilización por autoclave, según el manual de la WATO EX-20.</em>
</p>


Para los componentes autorizados, el manual señala una **temperatura máxima de 134 °C**, con tiempos recomendados que dependen del componente. Específicamente, para el **fuelle** indica **121 °C durante 20 minutos** o **134 °C durante 7 minutos**, mientras que para otros componentes compatibles incluye **134 °C durante 20 minutos**. Estos valores describen el manual consultado: **no deben aplicarse indiscriminadamente a accesorios de reemplazo o de otros fabricantes** [5].

> **Precaución:** No se debe esterilizar el conjunto completo sin desmontarlo ni asumir que todos sus sensores toleran altas temperaturas. Debe verificarse el marcado de cada pieza, el protocolo institucional de reprocesamiento y la versión del manual correspondiente al equipo. El absorbente químico de CO₂ se reemplaza conforme a las instrucciones del fabricante; no se esteriliza para volver a utilizarlo.

### d) ¿Cuántos y cuáles son los submenús del ventilador? ¿En qué consiste cada uno? ¿En cuál de ellos se puede activar la pausa inspiratoria?

En la pantalla principal de la **WATO EX-20**, el manual consultado describe **cuatro opciones principales de menú** asociadas con la gestión del equipo. Es importante distinguir estos menús de los **dos modos de ventilación mecánica** VCV y PCV, pues la pregunta puede interpretarse de ambas maneras. A continuación se presentan ambos conceptos [5].

#### Cuatro opciones principales de la interfaz


<table align="center">
  <thead>
    <tr>
      <th align="center">Opción de menú</th>
      <th align="center">¿Para qué sirve?</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><strong>Modo de ventilación</strong></td>
      <td align="center">Permite seleccionar el modo de ventilación mecánica y acceder a su configuración.</td>
    </tr>
    <tr>
      <td align="center"><strong>Configuración de alarmas</strong></td>
      <td align="center">Permite ajustar límites y opciones de alarma del ventilador y, si está instalado, del módulo de gases.</td>
    </tr>
    <tr>
      <td align="center"><strong>Configuración de usuario</strong></td>
      <td align="center">Agrupa ajustes de monitorización, presentación en pantalla, sonido y otros parámetros de configuración.</td>
    </tr>
    <tr>
      <td align="center"><strong>Mantenimiento</strong></td>
      <td align="center">Da acceso a funciones relacionadas con verificaciones, pruebas de fugas, calibraciones y ajustes técnicos, según permisos y configuración.</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 5. Opciones principales del menú de la máquina de anestesia WATO EX-20 y sus respectivas funciones.</em>
</p>

#### Modos de ventilación: VCV y PCV

**VCV — Ventilación controlada por volumen.** El operador selecciona el volumen corriente objetivo (VC), la frecuencia respiratoria y la relación entre los tiempos inspiratorio y espiratorio (I:E). La máquina busca administrar el volumen configurado, mientras la presión requerida depende de la mecánica respiratoria y de los límites de seguridad. Entre los parámetros de este modo están `VC`, `Frecuencia`, `I:E`, `TIP:TI`, `Plimit` y `PEEP` [5].

**PCV — Ventilación controlada por presión.** El operador selecciona la presión inspiratoria objetivo (`Pinsp`), la frecuencia, la relación `I:E`, el tiempo de ascenso de presión (`Tslope`) y la `PEEP`. En este caso, el volumen corriente resultante **no se fija directamente**: cambia según la resistencia, la distensibilidad y las condiciones del circuito y del paciente [5].


<table align="center">
  <thead>
    <tr>
      <th align="center">Característica</th>
      <th align="center">VCV</th>
      <th align="center">PCV</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Variable objetivo principal</td>
      <td align="center">Volumen corriente (VC)</td>
      <td align="center">Presión inspiratoria (Pinsp)</td>
    </tr>
    <tr>
      <td align="center">Variable que puede variar con la mecánica respiratoria</td>
      <td align="center">Presión inspiratoria</td>
      <td align="center">Volumen corriente</td>
    </tr>
    <tr>
      <td align="center">Parámetros característicos</td>
      <td align="center">VC, frecuencia, I:E, TIP:TI, Plimit, PEEP</td>
      <td align="center">Pinsp, frecuencia, I:E, Tslope, PEEP</td>
    </tr>
    <tr>
      <td align="center">Opción explícita <code>TIP:TI</code></td>
      <td align="center"><strong>Sí</strong></td>
      <td align="center">No aparece entre los ajustes indicados para PCV en este manual</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 6. Comparación de los modos de ventilación controlada por volumen (VCV) y controlada por presión (PCV) de la máquina de anestesia WATO EX-20.</em>
</p>


#### ¿Dónde se activa la pausa inspiratoria?

La **pausa o meseta inspiratoria programada** se configura en **VCV** mediante el parámetro **`TIP:TI`**, que representa la proporción del tiempo inspiratorio destinada a la meseta o pausa de flujo. Una vez suministrado el volumen correspondiente, esta fase contribuye a disponer de un intervalo durante el cual el flujo inspiratorio se reduce o se interrumpe, según el funcionamiento de la modalidad [5].

El manual documenta el ajuste `TIP:TI` como **desactivado o ajustable entre 5 % y 60 %**, en incrementos del **5 %**, dependiendo de la configuración. Esto no debe confundirse con mantener presionada una función de pausa manual ni con la medición aislada de presión meseta en otros equipos [5].

## Parte B

### Identificación de la máquina de anestesia

Durante el reconocimiento de laboratorio se observó una estación **Mindray WATO EX-20** con módulo de control de flujos, pantalla del ventilador, indicadores de presión, sistema respiratorio circular, recipiente absorbente de CO₂, campana del fuelle, tubuladuras y bolsa de ventilación manual. La parte frontal incorpora controles diferenciados para aire, óxido nitroso y oxígeno, así como indicadores de presión de las fuentes de gases [1], [5].

<p align="center">
<img width="500" height="666" alt="image" src="https://github.com/user-attachments/assets/a04f07da-b6c8-419e-9766-5ade4b791af4" />
</p>


<p align="center">
  <em>Fig. 1. Vista general de la estación Mindray WATO EX-20. Tomado de: Elaboración Propia.</em>
</p>

<p align="center">
<img width="500" height="666" alt="image" src="https://github.com/user-attachments/assets/bfbd2c6e-ad7b-4fef-9820-e0157e8a5182" />
</p>

<p align="center">
  <em>Fig. 2. Panel de flujómetros, mandos de gases y pantalla. Tomado de: Elaboración Propia.</em>
</p>

**Observación importante:** La estructura de montaje del vaporizador situada debajo de la pantalla se aprecia **sin un vaporizador instalado**. En consecuencia, es posible reconocer el lugar destinado al módulo, pero no examinar en estas imágenes el dial, la cámara o el mecanismo de carga de un vaporizador concreto.

### Identifique, ubique y explique la función de las siguientes partes

#### a) Vaporizador

El **vaporizador anestésico** es el módulo destinado a transformar un agente anestésico líquido volátil en vapor y dosificar su concentración en la mezcla de gases frescos. Su calibración y su diseño están asociados con el anestésico para el cual fue fabricado; por ello, no se pueden intercambiar indiscriminadamente agentes o vaporizadores. En el circuito neumático, el vaporizador se integra después del control del flujo de gases y antes de que la mezcla llegue a la salida de gases frescos [5], [6].

**Ubicación observada:** En la **zona frontal derecha, debajo de la pantalla**, se identifica la base o colector de montaje del vaporizador, con sus puntos de acoplamiento. No se observa el vaporizador acoplado en la sesión fotográfica.

**Función:** Introducir una concentración regulada de anestésico inhalatorio (por ejemplo, sevoflurano o isoflurano, según compatibilidad del vaporizador), contribuyendo al mantenimiento de la anestesia general [5], [6].

<p align="center">
<img width="500" height="529.1" alt="image" src="https://github.com/user-attachments/assets/bc3f15c7-00ae-442b-8b04-90e86fca3cc1" />
</p>

<p align="center">
  <em>Fig. 3. Área destinada al montaje del vaporizador. No se observa un vaporizador instalado. Tomado de: Elaboración Propia.</em>
</p>

#### b) Válvula APL

La **válvula APL** (*Adjustable Pressure Limiting*, limitadora ajustable de presión) permite regular el nivel al que se libera gas del circuito respiratorio durante la **ventilación manual**. Al aumentar la presión por encima del valor ajustado, la válvula deja salir el exceso hacia el sistema de evacuación de gases anestésicos, ayudando a evitar presiones excesivas dentro del circuito. No sustituye la supervisión continua de la presión de la vía aérea [5], [6].

**Ubicación observada:** En el módulo respiratorio lateral izquierdo, sobre la superficie superior gris, se aprecia una **perilla circular estriada marcada `APL cmH₂O`**. En la fotografía se distingue la escala graduada en centímetros de agua.

**Función:** Limitar la presión del circuito durante la ventilación manual y desviar el gas excedente hacia la evacuación. Su posición debe ser adecuada para la modalidad de uso; una regulación incorrecta puede causar escape excesivo de gas o presión elevada [5], [6].

<p align="center">
<img width="500" height="666" alt="image" src="https://github.com/user-attachments/assets/d6735910-9bd7-4caf-8767-0852733864e4" />
</p>

<p align="center">
  <em>Fig. 4. Perilla de la válvula APL. Tomado de: Elaboración Propia.</em>
</p>

#### c) Recipiente absorbente de CO₂

El **recipiente absorbente de dióxido de carbono** forma parte del sistema circular de anestesia. Aloja un material absorbente —habitualmente cal sodada— que elimina químicamente el CO₂ del gas espirado antes de que una fracción pueda recircular. De esta manera, ayuda a reducir el riesgo de reinhalación de dióxido de carbono cuando el circuito se utiliza en condiciones apropiadas [5], [6].

**Ubicación observada:** Corresponde al **contenedor cilíndrico transparente situado debajo del módulo de válvulas inspiratoria y espiratoria**. En su interior se observa una estructura central y un soporte perforado. En las imágenes **no puede confirmarse visualmente que contenga material absorbente en cantidad suficiente**, por lo que no debe asumirse que esté listo para uso clínico.

**Función:** Retener el absorbente de CO₂, mantenerlo integrado herméticamente al circuito y permitir la inspección visual del material. Un sellado incorrecto puede provocar fugas; un absorbente agotado puede permitir reinhalación de CO₂ [5], [6].

<p align="center">
<img width="500" height="790.5" alt="image" src="https://github.com/user-attachments/assets/a74f299d-b0cd-4f23-af39-1be648150562" />
</p>

<p align="center">
  <em>Fig.5. Recipiente absorbente de CO₂. Tomado de: Elaboración Propia.</em>
</p>

#### d) Fuelle

El **fuelle** (*bellows*) es el elemento flexible del ventilador de anestesia que se desplaza dentro de una cámara transparente durante la ventilación mecánica. El movimiento del fuelle está relacionado con la entrega y recuperación del volumen respiratorio en cada ciclo, de acuerdo con el diseño neumático de la estación [5], [6].

**Ubicación observada:** Se encuentra en la **parte superior del módulo respiratorio lateral izquierdo**, dentro de una campana cilíndrica transparente. En las fotografías se aprecia una estructura interna oscura y una pieza superior clara; dado que el equipo no aparece ventilando, no se dispone de evidencia del desplazamiento del fuelle.

**Función:** Participar en la transferencia del gas respiratorio durante la ventilación mecánica, permitiendo observar visualmente su movimiento. La campana, juntas y conexiones deben conservar la estanqueidad del sistema [5], [6].

<p align="center">
<img width="500" height="666" alt="image" src="https://github.com/user-attachments/assets/dde31aa1-2ab5-41c2-b515-dc9571bdf933" />
</p>

<p align="center">
  <em>Fig. 6. Campana transparente del fuelle y conjunto respiratorio. Tomado de: Elaboración Propia.</em>
</p>

### ¿Qué hacer si el ventilador muestra «Batería en uso» mientras el paciente está conectado?

El mensaje **«Battery in Use»** señala que la máquina está utilizando su batería interna en lugar del suministro eléctrico de corriente alterna. Esta condición puede presentarse por una desconexión accidental del cable, una interrupción de la red eléctrica o una anomalía en la alimentación. El manual de servicio indica comprobar primero la conexión a la fuente de CA [6].

Si existe un paciente conectado, la prioridad es **garantizar la continuidad de la ventilación y la oxigenación**, evitando que se agote la batería durante el procedimiento. El personal clínico debe verificar que el paciente continúe ventilándose adecuadamente, restaurar de inmediato la alimentación eléctrica segura y comprobar que el mensaje desaparezca y que los indicadores de alimentación correspondan a la condición normal. Debe informarse al anestesiólogo y al personal responsable; si no se recupera una fuente eléctrica confiable, se debe preparar una alternativa de ventilación segura y seguir el protocolo institucional, sin esperar a que la batería se descargue [5], [6].

Verificar de inmediato la conexión de corriente alterna, restablecerla si es seguro hacerlo, confirmar el funcionamiento del ventilador y mantener disponible una estrategia de ventilación alternativa. Si la falla persiste, retirar el equipo de servicio cuando el paciente se encuentre sostenido por un sistema alternativo seguro y solicitar revisión técnica [6].

### ¿Con qué frecuencia reemplazar el recipiente absorbente de CO₂?

Es importante diferenciar el **recipiente reutilizable** y el **material absorbente** que se coloca dentro. No existe una periodicidad universal fija para cambiar el recipiente completo. El absorbente se reemplaza **cuando se agota su capacidad de absorción**, atendiendo principalmente a la monitorización de CO₂ inspirado y a los indicios de agotamiento descritos por el fabricante. Su duración depende, entre otros factores, del flujo de gas fresco, el tiempo de uso y la producción de CO₂ del paciente [5].

El cambio de color de la cal sodada es una **señal orientativa, no una confirmación suficiente**: el fabricante advierte que el material puede recuperar parcialmente su color después de permanecer en reposo, aunque se haya utilizado. Por eso, debe emplearse el monitoreo de CO₂ y seguirse el programa de mantenimiento institucional [5].

Respecto al **recipiente**, debe inspeccionarse durante el reprocesamiento y reemplazarse si presenta grietas, deformaciones, daños en las uniones o defectos que comprometan el sellado. Después de desmontarlo y reinstalarlo debe verificarse la estanqueidad del circuito conforme al manual [5], [6].

El absorbente se cambia **según necesidad y capacidad de absorción**, no obligatoriamente cada cierto número de horas o días; el recipiente físico se sustituye si está defectuoso o según las indicaciones específicas de mantenimiento del fabricante.

### Procedimiento para verificar una fuga en un cilindro de alta presión

La sección **3.3.2, «Cylinder High Pressure Leak Test»** del manual de servicio describe una prueba basada en observar si la presión indicada disminuye durante un intervalo de un minuto tras cerrar la válvula del cilindro. La prueba se aplica individualmente a los cilindros configurados en el equipo [6].

**Secuencia documentada (solo para personal autorizado):**

1. Confirmar que el sistema se encuentra en el estado requerido por el manual y que el suministro alternativo de gases es adecuado.
2. Cerrar el flujómetro auxiliar de O₂, si existe, y ajustar los controles de flujo al mínimo.
3. Abrir lentamente la válvula del cilindro a comprobar y registrar la presión indicada en su manómetro.
4. Cerrar la válvula del cilindro; esperar **un minuto** y registrar nuevamente la presión.
5. Comparar ambas lecturas y determinar la caída de presión.
6. Repetir de manera independiente para cada cilindro configurado, siguiendo las medidas específicas del manual para O₂ y N₂O [6].

El manual establece los siguientes criterios de detección de fuga durante el minuto de observación:

<table align="center">
  <thead>
    <tr>
      <th align="center">Condición</th>
      <th align="center">Criterio de fuga según manual</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Cilindro que suministra gas impulsor (<em>drive gas</em>)</td>
      <td align="center">Caída <strong>mayor de 5000 kPa</strong> (725 psi)</td>
    </tr>
    <tr>
      <td align="center">Cilindro de gas no impulsor</td>
      <td align="center">Caída <strong>mayor de 690 kPa</strong> (100 psi)</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 7. Criterios de detección de fugas en cilindros de alta presión según el manual de la WATO EX-20.</em>
</p>

La disminución se obtiene mediante:

$$
\Delta P = P_{\mathrm{inicial}} - P_{\mathrm{final}}
$$

Si se supera el límite correspondiente, el manual indica reemplazar la junta del cilindro y repetir la comprobación. Si la fuga persiste, **el sistema no debe utilizarse** hasta que la anomalía sea corregida [6].

> **Registro experimental pendiente:** no se dispone de lecturas iniciales ni finales en las fotografías. No debe reportarse que la prueba fue superada sin haberla realizado.

### ¿Influye la presencia del sensor de O₂ en la prueba del control de flujo?

**Sí.** El manual de servicio separa la comprobación del control de flujo en dos procedimientos: **3.4.1, sin sensor de O₂**, y **3.4.2, con sensor de O₂** [6].

**Sin sensor de O₂:** La comprobación se centra en el movimiento correcto de los flotadores de los flujómetros y en la relación de flujos entre O₂ y N₂O mediante el sistema de interconexión (*Link*). Se comprueba que, al aumentar el flujo de N₂O, se mantenga un flujo mínimo de O₂ apropiado, y que al reducir O₂ también disminuya el N₂O. El manual proporciona pares de flujos mínimos para verificar la interconexión [6].

**Con sensor de O₂:** Primero debe verificarse la monitorización y las alarmas de concentración de oxígeno. El sensor debe estar **correctamente calibrado** y el sistema *Link* operativo. Durante las pruebas de aumento de N₂O y disminución de O₂, se verifica no solamente la respuesta de los flujómetros, sino que la **concentración de O₂ medida permanezca al menos en 25 %** a lo largo del rango evaluado, según el protocolo del manual [6].


<table align="center">
  <thead>
    <tr>
      <th align="center">Aspecto</th>
      <th align="center">Sin sensor de O₂</th>
      <th align="center">Con sensor de O₂</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Evidencia principal</td>
      <td align="center">Flujos indicados por rotámetros y acción del sistema <em>Link</em></td>
      <td align="center">Rotámetros, acción del <em>Link</em> y concentración medida</td>
    </tr>
    <tr>
      <td align="center">Prueba previa de concentración</td>
      <td align="center">No es la base de este procedimiento</td>
      <td align="center">Requiere comprobar monitorización/alarma y calibración</td>
    </tr>
    <tr>
      <td align="center">Verificación de mezcla</td>
      <td align="center">Indirecta, a través de los caudales</td>
      <td align="center">Directa, mediante concentración medida de O₂</td>
    </tr>
    <tr>
      <td align="center">Criterio destacado en el manual</td>
      <td align="center">Pares mínimos de caudal O₂/N₂O</td>
      <td align="center">Concentración medida de O₂ ≥ 25 %</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 8. Comparación de la prueba del sistema de control de flujo con y sin sensor de oxígeno en la máquina de anestesia WATO EX-20.</em>
</p>

La presencia del sensor permite verificar directamente el porcentaje de oxígeno suministrado; sin él, la prueba se basa en el comportamiento mecánico y la relación entre los flujos. La fotografía del equipo no permite establecer si el sensor opcional estaba conectado, operativo y calibrado [6].

### ¿Para qué se requiere el sistema de presión negativa?

La expresión **«sistema de presión negativa»** puede referirse a dos aplicaciones distintas asociadas con una estación de anestesia:

**1. Sistema de evacuación de gases anestésicos (AGSS).** Su función es recoger y evacuar los gases residuales procedentes del sistema respiratorio y de la válvula APL, reduciendo la exposición del personal a los anestésicos liberados en la sala. Cuando incorpora aspiración, la presión negativa facilita su traslado hacia un sistema de eliminación. El sistema debe estar diseñado para que la succión no se transmita de manera peligrosa al circuito del paciente [5], [6].

**2. Pruebas de estanqueidad con presión negativa.** El manual de servicio también describe pruebas técnicas de fugas del circuito neumático de baja presión mediante una **pera o bulbo de presión negativa** (*negative pressure ball*). Al evacuar el aire del bulbo y conectarlo a la parte aislada del sistema que se está evaluando, la recuperación de su volumen permite detectar posibles entradas de aire por fugas. Se utiliza para diagnosticar componentes como flujómetros, válvulas o el colector del vaporizador [6].

Si se refiere a la **presión negativa utilizada en mantenimiento**, su propósito es comprobar la hermeticidad de determinados segmentos del circuito neumático. Si se refiere a la **aspiración del sistema de evacuación**, su propósito es retirar los gases anestésicos residuales. Conviene confirmar con el docente cuál de ambos sistemas se abordó en la demostración; las fotografías no permiten identificar de forma concluyente la conexión a una instalación activa de evacuación [5], [6].

### Registro fotográfico complementario

<p align="center">
<img width="500" height="666" alt="image" src="https://github.com/user-attachments/assets/d02ac3aa-06c8-47e9-83c4-7f3490095ed4" />
</p>

<p align="center">
  <em>Fig. 7. Vista lateral del sistema respiratorio: bolsa de ventilación manual, mangueras corrugadas, recipiente de CO₂ y campana del fuelle. Tomado de: Elaboración Propia.</em>
</p>

En las fotografías también se distinguen válvulas unidireccionales bajo tapas transparentes, el manómetro de presión de vía aérea, dos conexiones principales del circuito respiratorio y los mandos de control de gases. La documentación visual es de **reconocimiento de partes**; no constituye evidencia de mantenimiento realizado ni de pruebas de funcionamiento exitosas.

#### Vista posterior y distribución de conexiones

<p align="center">
<img width="500" height="666" alt="image" src="https://github.com/user-attachments/assets/ec196e2b-c457-4f28-ab0e-53c6dbd5cc80" />
</p>

<p align="center">
  <em>Fig. 8. Vista posterior de la WATO EX-20, con mangueras de gases medicinales, cables y panel de conexiones. Tomado de: Elaboración Propia.</em>
</p>

La vista posterior muestra la **disposición de las conexiones neumáticas y eléctricas** del equipo. Se aprecian tres mangueras de suministro enrolladas —**verde, azul y amarilla**—, conectadas a entradas metálicas en el panel posterior. También se observan cables, puertos de comunicación, ventilación del gabinete y el conjunto respiratorio desde otro ángulo. Esta organización facilita identificar las interfaces externas de la estación y relacionarlas con el sistema de suministro de gases medicinales. En la fotografía no se observan cilindros conectados ni puede confirmarse el estado de presurización de las líneas o el funcionamiento de los subsistemas [5], [6].

#### Entradas de gases medicinales y codificación por color

<p align="center">
<img width="500" height="666" alt="image" src="https://github.com/user-attachments/assets/28d97ac5-1e91-4b7c-98e4-24c575f70ce3" />
</p>

<p align="center">
  <em>Fig. 9. Detalle de las entradas posteriores identificadas como N₂O, O₂ y AIR y sus mangueras correspondientes. Tomado de: Elaboración Propia.</em>
</p>

En el acercamiento se distinguen las etiquetas de tres entradas del sistema de suministro, cada una asociada con una manguera diferenciada:


<table align="center">
  <thead>
    <tr>
      <th align="center">Identificación visible</th>
      <th align="center">Color de manguera</th>
      <th align="center">Función del gas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><strong>N₂O</strong></td>
      <td align="center">Azul</td>
      <td align="center">Óxido nitroso: gas adyuvante para la anestesia inhalatoria.</td>
    </tr>
    <tr>
      <td align="center"><strong>O₂</strong></td>
      <td align="center">Verde</td>
      <td align="center">Oxígeno: permite aportar oxígeno a la mezcla respiratoria.</td>
    </tr>
    <tr>
      <td align="center"><strong>AIR</strong></td>
      <td align="center">Amarillo</td>
      <td align="center">Aire medicinal: participa como gas portador y en el ajuste de la mezcla.</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 9. Identificación de las conexiones de suministro de gases medicinales en la parte posterior de la máquina de anestesia WATO EX-20.</em>
</p>


Las inscripciones del panel indican un **intervalo de presión de suministro** junto a estas entradas. Se trata de conexiones reguladas de la red de gases medicinales; **no deben confundirse con las presiones internas de un cilindro de alta presión**. La identificación visible y la correspondencia de cada línea son útiles para comprender las rutas de alimentación de la máquina, pero las fotografías no permiten verificar la estanqueidad de las conexiones ni la calidad de los gases suministrados [5], [6].

**Observación de seguridad:** En un entorno clínico, la identificación de gases no debe basarse únicamente en el color de la manguera, ya que la codificación puede variar según la normativa. Se deben corroborar las etiquetas, el tipo de conector y las especificaciones del equipo. La conexión, desconexión y verificación funcional requieren personal autorizado y el procedimiento institucional correspondiente.

## Parte C.

## Análisis de resultados

### Fallas posibles en los subsistemas de la máquina de anestesia y sus causas

Una máquina de anestesia no depende de un único módulo. Su funcionamiento requiere coordinación entre la fuente de gases, los reguladores y controles de flujo, el sistema de vaporización, el circuito respiratorio, el ventilador, los sensores y las fuentes de alimentación. Una alteración en cualquiera de estos elementos puede generar una alarma, modificar la mezcla suministrada, alterar la presión o el volumen ventilatorio o impedir el funcionamiento esperado [5], [6].

#### Subsistema de suministro neumático

Las fallas relacionadas con la fuente de gases incluyen **pérdidas en mangueras o uniones, presión de entrada insuficiente, obstrucciones y fallas de reguladores o interruptores de presión**. Estas alteraciones pueden producir caudal inadecuado, interrupción del suministro o presión insuficiente del gas impulsor del ventilador. Las causas posibles comprenden conexiones defectuosas, empaques deteriorados, tuberías dañadas, cilindros descargados o problemas de la red hospitalaria [6].

En las fotografías posteriores se reconocieron las mangueras y sus conexiones, lo cual permite ubicar físicamente un posible punto de fuga. **Sin embargo, su apariencia externa no demuestra que existan fugas ni que las presiones sean correctas.** La prueba de estanqueidad debe realizarse siguiendo las instrucciones del fabricante y los protocolos del establecimiento [6].

#### Sistema de control y mezcla de gases

Este subsistema debe permitir una distribución controlada de O₂, aire y N₂O. Entre las fallas que pueden afectar su desempeño se encuentran **fugas en conexiones o controles, rotámetros con indicaciones incorrectas, elementos de regulación obstruidos y funcionamiento anómalo del mecanismo de proporción de oxígeno y óxido nitroso**. Las causas pueden incluir desgaste mecánico, contaminación, desajuste o daño de componentes [6].

La identificación de los flujómetros frontales ayudó a comprender la relación entre las fuentes de gas y la mezcla administrada. La **lectura de un rotámetro no sustituye la medición independiente de la concentración de oxígeno**, cuando esta se encuentra disponible y calibrada [5], [6].

#### Sistema de vaporización

El vaporizador debe aportar una concentración regulada de anestésico inhalatorio. Sus posibles problemas incluyen **fugas en el montaje, errores por selección de un agente incompatible, nivel insuficiente de anestésico y alteraciones en los mecanismos de dosificación**. La utilización de vaporizadores incorrectamente instalados o incompatibles puede producir desviaciones entre la concentración esperada y la suministrada [5], [6].

Durante la práctica se observó **el soporte del vaporizador vacío**, no había un vaporizador acoplado. Tampoco es posible evaluar su precisión mediante la evidencia disponible.

#### Circuito respiratorio y eliminación de CO₂

El circuito puede presentar **fugas en uniones o tubuladuras, válvulas unidireccionales que no cierran correctamente, conexiones mal ensambladas, exceso de resistencia y agotamiento del absorbente de CO₂**. Estos problemas pueden favorecer la pérdida de volumen, la reinhalación de CO₂, la alteración de la presión del circuito o una ventilación inefectiva [5], [6].

Las fotografías del laboratorio permitieron identificar tubos respiratorios, conectores, válvulas, bolsa manual, APL y recipiente del absorbente. No obstante, **la presencia del recipiente no permite conocer la capacidad remanente del material absorbente**. Esta se valora mediante las indicaciones del fabricante, el estado del absorbente y la vigilancia de CO₂ inspirado [5].

#### Ventilador mecánico y válvulas de control

Entre las fallas descritas se encuentran **presión inspiratoria no alcanzada, volumen corriente no alcanzado, irregularidades en la válvula PEEP o de seguridad, errores de control neumático y fallos de comunicación del módulo del ventilador**. Algunas pueden surgir por fugas en el circuito, presión impulsora insuficiente, problemas de sensores o mal funcionamiento de válvulas y tarjetas electrónicas [6].

Estas alteraciones son especialmente relevantes porque afectan directamente las variables utilizadas en los modos VCV y PCV. Un equipo puede tener configurado un volumen o una presión objetivo y, aun así, no conseguirlo debido a problemas físicos o de medición. Por esa razón, las alarmas del ventilador y los valores medidos son esenciales para la supervisión [5], [6].

#### Monitorización y sensores

El manual contempla alarmas vinculadas con **sensor de O₂ desconectado, necesidad de calibración del sensor de O₂, falla de sensores de flujo y problemas en la lectura de presión**. Entre las causas figuran desconexión de cables, agotamiento o deterioro de sensores, fallas en líneas de medición y errores de calibración [6].

La monitorización es importante porque un circuito puede parecer completo y, sin embargo, el sistema podría no medir correctamente el volumen, la presión o la concentración de oxígeno. Por tanto, la inspección visual debe complementarse con las comprobaciones operativas que correspondan [5], [6].

#### Alimentación eléctrica y sistema de control

Se consideran posibles **interrupciones de la alimentación de red, operación temporal con batería, fallas de tarjetas electrónicas, problemas de comunicación entre módulos y dificultades en el encendido o visualización de información**. Es necesario distinguir una **condición informativa de alimentación**, como «batería en uso», de una avería confirmada: ese mensaje puede indicar que la estación está funcionando desde su batería, por ejemplo, al perder alimentación externa [6].

En las fotografías se identifica el cable de alimentación posterior, pero no es posible establecer si el suministro eléctrico estaba disponible o si la batería funcionaba correctamente.

### Matriz de fallas, causas y consecuencias


<table align="center">
  <thead>
    <tr>
      <th align="center">Subsistema</th>
      <th align="center">Ejemplos de fallas o condiciones</th>
      <th align="center">Causas posibles</th>
      <th align="center">Efecto potencial</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Suministro neumático</td>
      <td align="center">Fugas; presión insuficiente; fallo del regulador</td>
      <td align="center">Mangueras, juntas o reguladores defectuosos</td>
      <td align="center">Menor disponibilidad de gas o pérdida de presión impulsora</td>
    </tr>
    <tr>
      <td align="center">Control y mezcla</td>
      <td align="center">Fuga interna; error de indicación; regulación inadecuada</td>
      <td align="center">Desgaste, obstrucción o desajuste</td>
      <td align="center">Caudales y composición de mezcla incorrectos</td>
    </tr>
    <tr>
      <td align="center">Vaporización</td>
      <td align="center">Fuga; dosificación incorrecta; incompatibilidad</td>
      <td align="center">Montaje o configuración inadecuados</td>
      <td align="center">Concentración anestésica no deseada</td>
    </tr>
    <tr>
      <td align="center">Circuito respiratorio</td>
      <td align="center">Fuga; obstrucción; válvulas defectuosas; absorbente agotado</td>
      <td align="center">Montaje incorrecto, desgaste, agotamiento del material</td>
      <td align="center">Pérdida de ventilación efectiva o reinhalación de CO₂</td>
    </tr>
    <tr>
      <td align="center">Ventilador</td>
      <td align="center">Volumen/presión no alcanzados; válvulas o control anómalos</td>
      <td align="center">Fuga, baja presión, sensor o actuador defectuoso</td>
      <td align="center">Parámetros ventilatorios fuera de objetivo</td>
    </tr>
    <tr>
      <td align="center">Sensores y monitorización</td>
      <td align="center">Sensor desconectado; calibración incorrecta; medición errónea</td>
      <td align="center">Desconexión, deterioro o defecto de calibración</td>
      <td align="center">Información poco confiable y alarmas técnicas</td>
    </tr>
    <tr>
      <td align="center">Alimentación y electrónica</td>
      <td align="center">Pérdida de red; fallos de comunicación o control</td>
      <td align="center">Alimentación interrumpida o fallas electrónicas</td>
      <td align="center">Dependencia de batería o degradación de funciones</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 10. Principales fallas, causas posibles y efectos asociados a los subsistemas de la máquina de anestesia WATO EX-20.</em>
</p>

### Orden de los subsistemas según el número de fallas asociadas

La guía solicita organizar los subsistemas de mayor a menor según el número de fallas asociadas [1]. Para no confundir **cantidad de modos de falla documentados** con **frecuencia de averías ocurridas**, se plantea un conteo explícito de **categorías distintas de fallas descritas en la matriz de este informe**, basado en los apartados de diagnóstico del manual [6].

**Criterio de conteo:** Cada modo de falla diferenciado en la lista siguiente se contabiliza una vez dentro del subsistema al que se asigna principalmente. Se trata de una **clasificación académica de un conjunto seleccionado de fallas**, no de un recuento exhaustivo de todas las filas del manual ni de estadísticas sobre fallas observadas en pacientes.


<table align="center">
  <thead>
    <tr>
      <th align="center">Orden</th>
      <th align="center">Subsistema</th>
      <th align="center">Modos de falla diferenciados en el análisis</th>
      <th align="center">Número</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">1</td>
      <td align="center">Circuito respiratorio</td>
      <td align="center">Fuga; obstrucción; válvula unidireccional defectuosa; absorbedor de CO₂ agotado; montaje incorrecto</td>
      <td align="center">5</td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td align="center">Suministro neumático</td>
      <td align="center">Fuga de línea; presión baja; obstrucción; falla del regulador</td>
      <td align="center">4</td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td align="center">Ventilador y válvulas</td>
      <td align="center">Presión objetivo no alcanzada; volumen objetivo no alcanzado; falla PEEP/seguridad; error de control o comunicación</td>
      <td align="center">4</td>
    </tr>
    <tr>
      <td align="center">4</td>
      <td align="center">Sensores y monitorización</td>
      <td align="center">Sensor desconectado; medición anómala; calibración fallida</td>
      <td align="center">3</td>
    </tr>
    <tr>
      <td align="center">4</td>
      <td align="center">Control y mezcla de gases</td>
      <td align="center">Fuga de control; indicación errónea; regulación anómala</td>
      <td align="center">3</td>
    </tr>
    <tr>
      <td align="center">6</td>
      <td align="center">Vaporización</td>
      <td align="center">Fuga de montaje; dosificación inadecuada; incompatibilidad de agente o equipo</td>
      <td align="center">3</td>
    </tr>
    <tr>
      <td align="center">6</td>
      <td align="center">Alimentación y electrónica</td>
      <td align="center">Pérdida de alimentación de red; falla de módulo o tarjeta; falla de comunicación</td>
      <td align="center">3</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 11. Clasificación de los subsistemas de la máquina de anestesia WATO EX-20 según el número de modos de falla diferenciados en el análisis.</em>
</p>

**Interpretación.** En la selección presentada, el circuito respiratorio reúne el mayor número de tipos de fallas diferenciados, debido a que incluye múltiples conexiones, válvulas y elementos que requieren ensamblaje, estanqueidad y mantenimiento. También destacan el suministro neumático y el ventilador, ya que de ellos depende la disponibilidad de gases y el cumplimiento de los parámetros de ventilación. Esto **no demuestra** que esos subsistemas fallen más frecuentemente en la práctica clínica: para establecer prevalencia sería necesario contar con registros de mantenimiento, alarmas y fallas de una población de equipos durante un periodo definido.

**Limitación metodológica:** Para cumplir la versión más estricta del análisis solicitado (conteo exhaustivo *de todas las entradas* del manual de servicio), debe elaborarse una matriz fila por fila de su capítulo 5, resolviendo primero cómo contabilizar causas múltiples, alarmas repetidas y fallas que involucran varios subsistemas. La tabla anterior es un **ordenamiento argumentado y reproducible de los modos de falla seleccionados**, no ese censo integral.

### Interpretación técnica y acciones preventivas

El análisis permite distinguir tres niveles de seguridad complementarios. El primero es la **integridad física**: conexiones correctas, tubos sin daños visibles, ausencia de obstrucciones y accesorios montados adecuadamente. El segundo es la **verificación funcional**: pruebas de fugas, comprobación de sensores, suministro de gas y funcionamiento de válvulas, ejecutadas según los protocolos técnicos. El tercero es la **vigilancia durante la operación**, mediante alarmas, monitorización respiratoria y verificación continua de las variables relevantes [5], [6].

Por ejemplo, una pérdida de presión en el circuito puede originarse en una conexión mal ajustada y no necesariamente en un daño del ventilador. De manera semejante, una alarma de volumen no alcanzado puede relacionarse con una fuga o con un problema de medición. Por ello, el diagnóstico requiere un procedimiento sistemático y no debe basarse en un único síntoma.

En la WATO EX-20 estudiada visualmente, las mangueras posteriores, los acoples respiratorios, la válvula APL, el recipiente del absorbente y el alojamiento del fuelle constituyen puntos importantes de reconocimiento y mantenimiento. La prioridad preventiva consiste en **realizar las inspecciones y pruebas prescritas antes del uso**, revisar las alarmas y retirar de servicio cualquier equipo que no cumpla con los criterios de seguridad, de acuerdo con la institución y el fabricante [5], [6].

## Preguntas para la discusión

### ¿Qué tipos de anestésicos son los más usados en cirugía?

Los fármacos anestésicos más empleados no pertenecen a una única familia, porque la anestesia quirúrgica suele combinar medicamentos con objetivos diferentes: producir hipnosis o inconsciencia, reducir el dolor, facilitar determinadas maniobras y mantener condiciones fisiológicas adecuadas. La selección depende del procedimiento, el paciente, la vía de administración y la valoración del equipo de anestesiología. En términos generales, deben distinguirse los **anestésicos intravenosos**, los **inhalatorios** y los **anestésicos locales**; otros grupos, como los opioides o los bloqueadores neuromusculares, se utilizan como coadyuvantes y **no todos son anestésicos generales por sí mismos** [2], [7].

#### a) Anestésicos generales intravenosos

Los agentes intravenosos se administran directamente al torrente sanguíneo y suelen utilizarse para la **inducción de la anestesia general**, es decir, el inicio de la pérdida de conciencia. Algunos también pueden utilizarse para mantener la anestesia mediante infusión continua. Su principal ventaja es que permiten una acción relativamente rápida y una dosificación ajustable [7].

- **Propofol:** uno de los fármacos más utilizados para inducir anestesia general y también para mantenerla mediante infusión. Produce hipnosis, pero **no proporciona analgesia suficiente por sí solo**; por eso suele combinarse con otros medicamentos cuando el procedimiento es doloroso [7].
- **Etomidato:** agente hipnótico intravenoso utilizado en determinadas situaciones clínicas, especialmente cuando se busca reducir ciertos efectos hemodinámicos respecto de otras alternativas. La elección requiere valorar sus efectos adversos y el contexto del paciente [7].
- **Ketamina:** fármaco con propiedades anestésicas y analgésicas, que produce un estado disociativo. Puede ser útil en situaciones seleccionadas por sus características farmacológicas; no es intercambiable con otros hipnóticos y su uso depende de la indicación clínica [7].

#### b) Anestésicos generales inhalatorios

Los anestésicos inhalatorios se administran a través del sistema respiratorio y permiten mantener la anestesia ajustando la concentración administrada. Los agentes volátiles se presentan como líquidos que requieren un **vaporizador compatible** para incorporarse de manera regulada a la mezcla de gases frescos. La máquina de anestesia cumple aquí una función fundamental en la administración, ventilación y monitorización [5], [7].

- **Sevoflurano:** agente volátil de amplio uso clínico para el mantenimiento de la anestesia y, en determinadas circunstancias, para la inducción inhalatoria, por sus características de tolerabilidad y control.
- **Isoflurano:** anestésico volátil utilizado para mantener la anestesia general; su perfil farmacológico y disponibilidad pueden determinar su elección.
- **Desflurano:** anestésico volátil de acción y eliminación relativamente rápidas, cuya utilización depende de la infraestructura, los requisitos del vaporizador y las prácticas institucionales. Su uso ha disminuido en algunos contextos por consideraciones ambientales y clínicas, por lo que no debe suponerse que sea uno de los más frecuentes en todos los hospitales.
- **Óxido nitroso (N₂O):** gas con efectos analgésicos y anestésicos limitados, habitualmente empleado como coadyuvante y no como anestésico general único para cirugía mayor [7].

#### c) Anestésicos locales y regionales

Los anestésicos locales bloquean de forma reversible la transmisión nerviosa en la zona donde se aplican. Pueden emplearse por infiltración local o como parte de técnicas regionales, como bloqueos de nervios periféricos o anestesia neuroaxial. Entre los ejemplos de uso habitual se encuentran **lidocaína, bupivacaína y ropivacaína**. Su selección depende de la duración deseada, la región anatómica, la dosis segura y otras condiciones clínicas. A diferencia de los anestésicos inhalatorios, estos fármacos no se administran mediante el vaporizador de la WATO EX-20 [2], [4].

#### d) Medicamentos complementarios a la anestesia

En cirugía también se utilizan **opioides** como fentanilo para analgesia y **bloqueadores neuromusculares** como rocuronio para facilitar la intubación o determinadas intervenciones. Aunque forman parte del manejo anestésico, **no reemplazan al hipnótico o al agente anestésico necesario para producir inconsciencia**; de hecho, la parálisis muscular por sí sola no equivale a anestesia [7].


<table align="center">
  <thead>
    <tr>
      <th align="center">Grupo</th>
      <th align="center">Ejemplos</th>
      <th align="center">Finalidad principal</th>
      <th align="center">Relación con la WATO EX-20</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Hipnóticos intravenosos</td>
      <td align="center">Propofol, etomidato, ketamina</td>
      <td align="center">Inducción y, según el fármaco, mantenimiento de anestesia</td>
      <td align="center">Se administran mediante dispositivos intravenosos externos, no por el vaporizador</td>
    </tr>
    <tr>
      <td align="center">Inhalatorios volátiles</td>
      <td align="center">Sevoflurano, isoflurano, desflurano</td>
      <td align="center">Mantenimiento de anestesia general; algunos permiten inducción</td>
      <td align="center">Requieren vaporizador apropiado y sistema de suministro de gases</td>
    </tr>
    <tr>
      <td align="center">Gas anestésico coadyuvante</td>
      <td align="center">Óxido nitroso</td>
      <td align="center">Analgesia y apoyo a la técnica anestésica</td>
      <td align="center">Se incorpora mediante el circuito de gases cuando está disponible</td>
    </tr>
    <tr>
      <td align="center">Anestésicos locales</td>
      <td align="center">Lidocaína, bupivacaína, ropivacaína</td>
      <td align="center">Bloqueo nervioso local o regional</td>
      <td align="center">No dependen del vaporizador de la máquina</td>
    </tr>
    <tr>
      <td align="center">Analgésicos y relajantes coadyuvantes</td>
      <td align="center">Fentanilo, rocuronio</td>
      <td align="center">Analgesia y relajación muscular, respectivamente</td>
      <td align="center">Se administran por otras vías y no sustituyen la hipnosis</td>
    </tr>
  </tbody>
</table>

<p align="center">
  <em>Tabla 12. Clasificación de los principales agentes farmacológicos utilizados en anestesia y su relación con la máquina de anestesia WATO EX-20.</em>
</p>

La WATO EX-20 está diseñada principalmente para suministrar y controlar gases medicinales y agentes anestésicos inhalatorios por medio de sus sistemas neumáticos y de vaporización. Su participación en una anestesia general no implica que todos los fármacos utilizados durante la cirugía pasen por la máquina: los anestésicos intravenosos, anestésicos locales, analgésicos y relajantes musculares se administran mediante otras vías y dispositivos. Por tanto, desde la ingeniería biomédica se deben reconocer tanto las funciones del equipo como los límites de su intervención en el procedimiento [5], [7].

### ¿Qué diferencias plantea el modelo WATO EX-35 con respecto al WATO EX-20?

La **WATO EX-20** y la **WATO EX-35** pertenecen a la familia de estaciones de anestesia de Mindray y comparten principios fundamentales: suministro de gases medicinales, integración de vaporizadores, sistema respiratorio circular, ventilación mecánica y vigilancia de parámetros respiratorios. La EX-35, sin embargo, incorpora características que amplían la capacidad de configuración del ventilador y la interacción con el usuario, según la versión y las opciones instaladas [5], [6], [8], [9].

#### a) Pantalla e interfaz de usuario

La WATO EX-20 estudiada en la práctica dispone de una pantalla con controles físicos y un banco de flujómetros mecánicos. En las fichas técnicas comparativas consultadas se describe una pantalla de aproximadamente **7 pulgadas** para la EX-20 y una pantalla **táctil de 10,4 pulgadas** para la EX-35. Esto supone una diferencia en la visualización y el acceso a los parámetros, aunque las características exactas dependen de la configuración comercial del equipo [5], [9].

#### b) Modalidades de ventilación

El modelo EX-20 analizado en la Parte A describe las modalidades mecánicas **VCV** (control por volumen) y **PCV** (control por presión), además de la ventilación manual. La ficha oficial de la EX-35 incorpora **SIMV** (ventilación mandatoria intermitente sincronizada, tanto controlada por volumen como por presión) y **PS** (soporte de presión con respaldo ante apnea) dentro de sus especificaciones. Esta ampliación permite disponer de estrategias adicionales de soporte respiratorio, particularmente relevantes cuando se busca sincronización con esfuerzos respiratorios espontáneos [5], [8].

La presencia de una modalidad en una ficha técnica no garantiza que esté habilitada en cada estación: deben verificarse versión del software, accesorios y opciones instaladas.

#### c) Rango de volumen corriente y pacientes

Para la EX-20, el catálogo comparativo consultado informa un rango de **40 a 1500 mL** y aplicaciones pediátricas y de adultos; la EX-35 presenta un rango de **20 a 1500 mL en ventilación por volumen**, según la ficha oficial de Mindray, con referencia a pacientes adultos, pediátricos y lactantes. La capacidad de administrar volúmenes más bajos puede ampliar los escenarios clínicos contemplados, **pero no demuestra por sí sola aptitud universal para neonatos**: deben considerarse los criterios del fabricante, precisión de medición y accesorios disponibles [8], [9].

#### d) Monitorización y funciones de apoyo

La ficha oficial de la EX-35 indica funciones como **compensación automática de la distensibilidad del circuito**, compensación de fugas y almacenamiento de tendencias de parámetros. También detalla posibilidades de monitorización de volúmenes, presiones, resistencia y distensibilidad respiratoria. Estas características representan un conjunto de herramientas de supervisión y adaptación; no sustituyen la verificación periódica del equipo ni las valoraciones clínicas [8].

#### e) Comparación resumida

<table align="center">
  <thead>
    <tr><th align="center">Característica</th><th align="center">WATO EX-20</th><th align="center">WATO EX-35</th></tr>
  </thead>
  <tbody>
    <tr><td align="center">Pantalla</td><td align="center">Aprox. 7 pulgadas</td><td align="center">10,4 pulgadas, táctil</td></tr>
    <tr><td align="center">Flujometría descrita en catálogo</td><td align="center">Mecánica</td><td align="center">Visualización electrónica</td></tr>
    <tr><td align="center">Modos mecánicos principales</td><td align="center">VCV y PCV</td><td align="center">VCV, PCV y SIMV; soporte de presión según ficha y configuración</td></tr>
    <tr><td align="center">Volumen corriente en modo volumen</td><td align="center">40–1500 mL según catálogo</td><td align="center">20–1500 mL según ficha oficial</td></tr>
    <tr><td align="center">Grupos de pacientes descritos</td><td align="center">Adultos y pediátricos</td><td align="center">Adultos, pediátricos y lactantes, según especificación</td></tr>
    <tr><td align="center">Funciones complementarias destacadas</td><td align="center">Ventilación controlada por volumen/presión y controles mecánicos de flujo</td><td align="center">Más estrategias ventilatorias, compensaciones y tendencias de monitorización</td></tr>
  </tbody>
</table>

<p align="center"><em>Tabla 13. Comparación técnica general entre las estaciones de anestesia WATO EX-20 y WATO EX-35 [5], [8], [9]. Las funciones dependen de la versión y configuración comercial.</em></p>

La principal diferencia no es que la EX-35 realice una función completamente distinta, sino que ofrece una **interfaz y un conjunto de modalidades de ventilación más amplios** en las versiones documentadas. En términos de gestión tecnológica, esto implica revisar las necesidades del servicio clínico, la capacitación de usuarios, los consumibles y accesorios compatibles, las tareas de mantenimiento y la disponibilidad de soporte técnico antes de decidir entre equipos. Una estación con más opciones no será automáticamente la mejor elección si esas opciones no corresponden a la población de pacientes, la infraestructura y los procedimientos de la institución.

## Conclusiones

El desarrollo de la práctica permitió comprender el funcionamiento de la máquina de anestesia Mindray WATO EX-20 a partir del reconocimiento de sus componentes principales, la identificación de sus subsistemas y el análisis de las condiciones que pueden comprometer su operación. Mediante la inspección visual del equipo y la revisión de la documentación técnica, se identificaron elementos como la válvula APL, el fuelle, el recipiente absorbente de CO₂, el circuito respiratorio y las conexiones de suministro de gases medicinales, estableciendo la función de cada uno dentro de los procesos de ventilación y administración de mezclas gaseosas. Asimismo, el estudio de los modos de ventilación controlada por volumen (VCV) y por presión (PCV) permitió reconocer las diferencias en sus parámetros de funcionamiento y la necesidad de supervisar variables como la presión, el volumen corriente y la concentración de oxígeno. El análisis de las posibles fallas evidenció que el circuito respiratorio, el suministro neumático y el ventilador concentran una mayor diversidad de modos de falla dentro de la clasificación realizada, especialmente aquellos relacionados con fugas, obstrucciones, conexiones inadecuadas y alteraciones en la regulación de presión; sin embargo, esta clasificación no representa una medición de la frecuencia real de averías. Estos hallazgos permiten establecer que la seguridad del equipo no depende únicamente de su capacidad tecnológica, sino también de la correcta instalación de sus componentes, la verificación de las conexiones, la calibración de sensores, la respuesta oportuna a las alarmas y la ejecución de procedimientos de mantenimiento preventivo. Desde la perspectiva de la ingeniería biomédica, la práctica permitió relacionar los principios de instrumentación, control y monitorización con las necesidades de seguridad presentes en los entornos quirúrgicos, destacando que el reconocimiento de los subsistemas facilita la identificación de riesgos y la orientación de actividades de inspección y diagnóstico. Como siguiente paso, se propone complementar el reconocimiento visual con pruebas funcionales supervisadas, verificaciones de estanqueidad y evaluación de alarmas conforme a los procedimientos establecidos por el fabricante, con el propósito de contrastar el análisis teórico con mediciones experimentales y fortalecer los criterios técnicos necesarios para garantizar un funcionamiento confiable de la máquina de anestesia.


## Referencias bibliográficas

[1] Universidad Militar Nueva Granada, *Guía de preparación de práctica de laboratorio: Reconocimiento de partes y funcionamiento de una máquina de anestesia*, asignatura Instrumentación Biomédica y Biosensores, revisión 3, 30 de septiembre de 2025. Material suministrado en clase.

[2] U.S. National Library of Medicine, "Anestesia", *MedlinePlus*. [En línea]. Disponible en: https://medlineplus.gov/spanish/anesthesia.html

[3] American Society of Anesthesiologists, *Outpatient Surgery and Anesthesia*. [En línea]. Disponible en: https://madeforthismoment.asahq.org/wp-content/uploads/2021/07/ASA-293-OutPatient-Surgery-and-Anesthesia-ec-1.5.pdf

[4] Weill Cornell Medicine, Department of Anesthesiology, "Types of Anesthesia Care". [En línea]. Disponible en: https://anesthesiology.weill.cornell.edu/patients/types-anesthesia

[5] Shenzhen Mindray Bio-Medical Electronics Co., Ltd., *WATO EX-20: Manual do usuário*, edición de julio de 2018, capítulos 2–4, 6 y 10. [En línea]. Disponible en: https://cleanmedical.com.br/wp-content/uploads/2023/06/Manual-Usuario_Aparelho-Anestesia_Mindray-WATO-EX-20.pdf

[6] Shenzhen Mindray Bio-Medical Electronics Co., Ltd., *WATO EX-20/30/35 Anesthesia Machine: Service Manual*, versión 9.0, secciones 3.3 "Cylinder Tests", 3.4 "Flow Control System Tests", 5 "Troubleshooting" y 5.3 "Pneumatic Circuit System Problems". [En línea]. Disponible en: https://studylib.net/doc/27732005/wato-ex-20and30and35-service-manual-v9.0-en

[7] Anesthesia Patient Safety Foundation, "What Drugs Are Used in Anesthesia?", *APSF Patient Guide*. [En línea]. Disponible en: https://www.apsf.org/patient-guide/what-drugs-are-used-in-anesthesia/

[8] Shenzhen Mindray Bio-Medical Electronics Co., Ltd., *WATO EX-35: Anesthesia Machines — Specifications*. [En línea]. Disponible en: https://www.mindray.com/content/dam/xpace/en_gb/resources/downloads/products/anesthesia/wato-ex-35/specifications/WATO-EX-35-Specifications.pdf

[9] COSAMED, *Catálogo general de equipos médicos*, apartado "Máquinas de anestesia", tabla comparativa Mindray WATO EX-20 y WATO EX-35, 2024. [En línea]. Disponible en: https://cosamed.com/wp-content/uploads/2024/07/CATALOGO-GENERAL_TS2024.pdf

