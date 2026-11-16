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
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/bfbd2c6e-ad7b-4fef-9820-e0157e8a5182" />
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

### 4.6. Pregunta 5. ¿Influye la presencia del sensor de O₂ en la prueba del control de flujo?

**Sí.** El manual de servicio separa la comprobación del control de flujo en dos procedimientos: **3.4.1, sin sensor de O₂**, y **3.4.2, con sensor de O₂** [6].

**Sin sensor de O₂:** la comprobación se centra en el movimiento correcto de los flotadores de los flujómetros y en la relación de flujos entre O₂ y N₂O mediante el sistema de interconexión (*Link*). Se comprueba que, al aumentar el flujo de N₂O, se mantenga un flujo mínimo de O₂ apropiado, y que al reducir O₂ también disminuya el N₂O. El manual proporciona pares de flujos mínimos para verificar la interconexión [6].

**Con sensor de O₂:** primero debe verificarse la monitorización y las alarmas de concentración de oxígeno. El sensor debe estar **correctamente calibrado** y el sistema *Link* operativo. Durante las pruebas de aumento de N₂O y disminución de O₂, se verifica no solamente la respuesta de los flujómetros, sino que la **concentración de O₂ medida permanezca al menos en 25 %** a lo largo del rango evaluado, según el protocolo del manual [6].

| Aspecto | Sin sensor de O₂ | Con sensor de O₂ |
|---|---|---|
| Evidencia principal | Flujos indicados por rotámetros y acción del sistema *Link* | Rotámetros, acción del *Link* y concentración medida |
| Prueba previa de concentración | No es la base de este procedimiento | Requiere comprobar monitorización/alarma y calibración |
| Verificación de mezcla | Indirecta, a través de los caudales | Directa, mediante concentración medida de O₂ |
| Criterio destacado en el manual | Pares mínimos de caudal O₂/N₂O | Concentración medida de O₂ ≥ 25 % |

**Respuesta:** la presencia del sensor permite verificar directamente el porcentaje de oxígeno suministrado; sin él, la prueba se basa en el comportamiento mecánico y la relación entre los flujos. La fotografía del equipo no permite establecer si el sensor opcional estaba conectado, operativo y calibrado [6].

### 4.7. Pregunta 6. ¿Para qué se requiere el sistema de presión negativa?

La expresión **«sistema de presión negativa»** puede referirse a dos aplicaciones distintas asociadas con una estación de anestesia:

**1. Sistema de evacuación de gases anestésicos (AGSS).** Su función es recoger y evacuar los gases residuales procedentes del sistema respiratorio y de la válvula APL, reduciendo la exposición del personal a los anestésicos liberados en la sala. Cuando incorpora aspiración, la presión negativa facilita su traslado hacia un sistema de eliminación. El sistema debe estar diseñado para que la succión no se transmita de manera peligrosa al circuito del paciente [5], [6].

**2. Pruebas de estanqueidad con presión negativa.** El manual de servicio también describe pruebas técnicas de fugas del circuito neumático de baja presión mediante una **pera o bulbo de presión negativa** (*negative pressure ball*). Al evacuar el aire del bulbo y conectarlo a la parte aislada del sistema que se está evaluando, la recuperación de su volumen permite detectar posibles entradas de aire por fugas. Se utiliza para diagnosticar componentes como flujómetros, válvulas o el colector del vaporizador [6].

**Respuesta:** si la pregunta se refiere a la **presión negativa utilizada en mantenimiento**, su propósito es comprobar la hermeticidad de determinados segmentos del circuito neumático. Si se refiere a la **aspiración del sistema de evacuación**, su propósito es retirar los gases anestésicos residuales. Conviene confirmar con el docente cuál de ambos sistemas se abordó en la demostración; las fotografías no permiten identificar de forma concluyente la conexión a una instalación activa de evacuación [5], [6].

### 4.8. Registro fotográfico complementario

![Vista lateral del circuito respiratorio y bolsa manual](images/vista-lateral-circuito.png)

*Figura B7. Vista lateral del sistema respiratorio: bolsa de ventilación manual, mangueras corrugadas, recipiente de CO₂ y campana del fuelle. Fotografía propia.*

En las fotografías también se distinguen válvulas unidireccionales bajo tapas transparentes, el manómetro de presión de vía aérea, dos conexiones principales del circuito respiratorio y los mandos de control de gases. La documentación visual es de **reconocimiento de partes**; no constituye evidencia de mantenimiento realizado ni de pruebas de funcionamiento exitosas.
