# Equipo y mezcla

Lo que Ana tiene, lo que quiere armar y lo que se fue decidiendo. Claude es
la ingeniera tech y de sonido del proyecto: leer esto antes de asesorar
sobre equipo y actualizarlo cuando algo cambie. Cada instrumento tiene su
propio archivo en `instrumentos/`.

**Última actualización:** 2026-11-10

## Retomar acá (11/11/2026)

Ana sumó una **Technics SL-1700 MK2** (Pearl montada y ajustada). La **SL-D3 está a la venta** (~1 mes) para ir hacia
las SL-1200. Estilo que quiere para mezclar: **del trip hop al psy trance**, con isolator. No le interesa el scratch. El
K.O. queda para casa, no para tocar en vivo.

**Set sugerido por Claude (10/11/2026), a confirmar por Ana:** mixer **Pacson PM-3AL** (si lo prueba en persona y el
restaurador lo revisa, porque no tiene garantía); auriculares **Beyerdynamic DT 770 Pro**; cápsulas **Ortofon Concorde
MkII Club** (a confirmar el modelo); slipmats; par de **SL-1200 hechas en Japón** (MK5 o MK3D). Orden: mixer y
auriculares → primera 1200 con Concorde → segunda 1200. Abierto: mensaje a Pacson (precio, negra o roja, service,
prueba), foto de la chapa de abajo de la 1700 (voltaje y selector). Ya se le explicó: EQ por canal y pase de graves
("un solo bajo a la vez"), booth (parlante de cabina) y rec (grabar la mezcla; a la Mac va con una interfaz de audio USB). Comparados el Pacson PM-3AL y el Pioneer
DJM-250MK2 (tabla abajo): sigue ganando el Pacson si la prueba sale bien y el precio queda por debajo del Pioneer.

**Segunda bandeja para practicar (13/11/2026):** un amigo de Ana tiene una **Audio-Technica AT-LP120XBT-USB**
(tracción directa, manual, pitch ±8/±16 %, preamplificador interno con llave PHONO/LINE, headshell desmontable). Sirve
para probar un set juntos con la SL-1700 MK2 mientras no lleguen las 1200: va por cable RCA (el Bluetooth no sirve para
mezclar). Falta el mixer, que lo compraría Ana (el amigo no tiene): refuerza el orden "mixer primero".

**Idea nueva (11/11/2026): bandeja simulada propia.** Ana vio [vinyl-gl.vercel.app](https://vinyl-gl.vercel.app)
(código: [rauchg/vinyl](https://github.com/rauchg/vinyl), licencia MIT): una bandeja en WebGL que corta el surco y lo
lee con una púa simulada. El diseño es claramente una Technics SL-1210 (estroboscopio, pitch deslizante, brazo en S), sin
nombrarla; brazo de 228,6 mm. Plan propuesto: copiarlo en una carpeta `bandeja/` de este repo (dejando el aviso MIT del
autor) y adaptarlo a la **SL-1700 MK2 plateada** (brazo de 230 mm, overhang de 15 mm, offset de 22°, plato de 332 mm,
cuarzo) con la **Sumiko Pearl** (elíptica 0,3 × 0,7, 2,0 g, compliance 12). Sus discos se cortan solo en el navegador:
no se suben audios con derechos al repo. **Falta:** el "sí" de Ana para arrancar y fotos de la 1700 (arriba, costado y el
brazo con la Pearl).

## Objetivo

Aprender a **mezclar vinilos** (DJ) en vivo, sin descartar el sampleo. Enfoque
artesanal y barato: aprovechar lo que ya tiene y priorizar la calidad de la
mezcla y del sonido antes que gastar en equipo. Estilo (10/11/2026): **del trip hop al psy trance**, mezclas largas con isolator; el scratch no le interesa. Lo que más disfruta es buscar
discos y encontrar temas para samplear.

Plan con Seba: usar la bandeja en un evento más grande, donde haría falta más
potencia que la del equipo de casa.

## Lo que tiene hoy

| Equipo | Estado | Notas |
|---|---|---|
| Technics **SL-1700 MK2** (1977–79, hecha en Japón) | Nueva (nov. 2026) | Directa, motor de CC con **cuarzo** (PLL), semiautomática (se usa manual o con retorno automático), **pitch ±6 %**, plato de aluminio de 332 mm. Brazo estático de 230 mm, fuerza de apoyo de 0 a 2,5 g. Cables RCA fijos. W&F 0,025 % WRMS (hifi-wiki). El lift automático usa una correíta de goma que con los años se rompe: tiene repuesto. Cápsula original: Technics EPC-207C (si aparece, guardarla). Toda original salvo la púa (Pearl). Usa **trafo** externo; la conversión a 220 V la haría el restaurador de forma reversible (ver "Coleccionable" abajo). Headshell desmontable a confirmar con foto. Con un headshell por cápsula se cambia de "escuchar" a "tocar" en segundos. |
| Technics **SL-D3** (1978–80) | Restaurada a nuevo | Directa, B-FG servo (sin cuarzo), **totalmente automática**, pitch ±10 % con estroboscopio, 33/45, plato de aluminio de 312 mm. Brazo estático de 230 mm con fuerza de apoyo regulable de 0 a 2,5 g y antiskating. Wow & flutter de 0,03 % WRMS y rumble de −75 dB. Es para escuchar, no para mezclar (ver abajo). **A la venta** (nov. 2026), para ir hacia las 1200. |
| Cápsula **Sumiko Pearl** (MM, hecha en Japón) | Montada en la **SL-1700 MK2**, ajustada (nov. 2026) | Púa elíptica de 0,3×0,7 mil y cantiléver de aluminio. Salida de 4 mV, carga de 47 kΩ y 100–200 pF. Compliance de 12 cu y peso de 6 g. **Fuerza de apoyo: 2,0 g** (rango 1,5–2,0), con el antiskating en el mismo valor. Repuesto: aguja RS Pearl. Con el brazo de la SL-D3 la resonancia daba ~10–11 Hz (estimado). Para mezclar suave sirve; para scratch y backcue fuerte, la cápsula DJ. |
| Amplificador **Lenco A600** (1978) | Restaurado | Integrado de fines de los 70, hecho en Corea por un fabricante OEM y vendido con la marca suiza (según hifi-wiki). 2×60 W en 8 Ω y 2×120 W en 4 Ω. Ecualizador gráfico de 5 bandas (40 Hz, 250 Hz, 1 kHz, 5 kHz y 15 kHz, ±10 dB), vúmetros, loudness, mono/stereo y salidas de bafles A/B. Entradas: PHONO 1 y 2, TUNER, AUX 1 y 2, TAPE 1 y 2 (con monitor y dubbing). La bandeja va en PHONO. Tiene **REC out de TAPE 2 en el frente** (confirmado con foto, 26/10/2026). |
| Bafles **Technics** vintage | Restaurados | Conectados al Lenco. Falta confirmar el modelo (chapa de atrás). |
| TV **LG OLED** + DAC | Funciona | El audio de la TV va: salida óptica (Toslink) → DAC (a RCA, alimentado por USB) → **AUX** del Lenco. Nunca a PHONO. |
| Auriculares **AKG MKII** | Funcionan | **Semiabiertos** (confirmado por Ana): sirven para escuchar en casa; para pinchar conviene unos cerrados. |
| **Teenage Engineering EP-133 K.O. II** (Champ Edition, 64 MB) | Funciona | Sampler. **OS 2.5.1** (actualizado desde la 1.2.3 el 21/10/2026): ya tiene audio por USB. Todo lo del K.O. está en [`instrumentos/ko-ii.md`](instrumentos/ko-ii.md). |
| Mac M1 + Mac i7 2015 | Funcionan | La i7 se puede dedicar entera a esto. |
| Restaurador de confianza | — | "Excelente" según Ana. Hace que convenga comprar usado. |

## Plan: bandejas para mezclar (Technics SL-1200 / 1210)

Para mezclar hacen falta **dos bandejas iguales** con pitch (más un mixer de
2 canales y dos cápsulas iguales). La SL-D3 no reemplaza a una de las dos: es automática, tiene poco torque y no tiene cuarzo.

### Recomendación

1. **Primera opción: un par de SL-1200/1210 MK5 usadas**, revisadas por el
   restaurador. Son las mejores Technics "clásicas": tienen botón de reset
   del pitch, la altura del brazo es más fácil de ajustar, los pies aíslan
   mejor y el pitch no tiene el "clic" del cero. Se fabricaron hasta 2010.
2. **Segunda opción, más barata: un par de MK2** (desde 1979). Es el
   estándar histórico y son indestructibles. Con el restaurador se les puede
   hacer service completo (capacitores, potenciómetro del pitch, rulemanes
   del brazo) y agregarles salidas RCA en vez del cable soldado.
3. **Nuevas: SL-1200MK7.** Traen garantía, motor coreless, reversa, pitch de
   ±8/16 % y cables desmontables. Salen bastante más caras y con un
   restaurador bueno no hacen falta.
4. Evitar para mezclar: GR, G y GAE, que son modelos hi-fi. Son hermosas,
   pero no están pensadas para DJ.

### Las versiones (MK) de la serie clásica (consultado 2026-11-02)

Las fuentes no coinciden en algunos años (se ven ±1). Ninguna tiene "MK" que cambie el sonido de fondo:
es la misma máquina, refinada.

| Modelo | Año | Qué cambió | Para Ana |
|---|---|---|---|
| SL-1200 (original) | 1972 | Hi-fi, pitch giratorio | Solo pieza histórica |
| **MK2** | 1979 | Pitch deslizante ±8 %, cuarzo, aislación: el estándar DJ | Clásica, la más fácil de conseguir y de reparar |
| MK3 | 1989 | Igual a la MK2 por dentro (mismo motor y brazo): RCA dorados, logo dorado atrás, negro mate. Solo Japón | Rareza para coleccionar; para mezclar, igual que una MK2 |
| MK3D / M3D | 1997 | Sin el "clic" del cero (Technics dice que mejora la precisión cerca de 0), botón de reset del pitch, interruptor hundido, otro color de estrobo. MK3D = japonesa negra con RCA dorados; 1200M3D plateada / 1210M3D negra = exportación | **Muy buena para mezclar**: tiene lo esencial de la MK5 y suele salir más barata |
| MK4 | 1997 | 78 rpm y cables RCA desmontables; pensada para hi-fi | Solo Japón y Asia (100 V); no la mejor para mezclar |
| **MK5** | 2002 | Antiskating de 0-6 g (antes 0-3), ajuste de altura del brazo más fácil, reset del pitch, luz blanca | La mejor relación calidad/precio de las clásicas |
| MK5G | 2002 | Pitch ±16 % y luces azules | Lujo, no hace falta |
| **MK6** | 2007-08 | Mejor amortiguación, montaje del brazo, cableado y precisión del pitch | La última y más refinada de la serie clásica (discontinuada en 2010) |
| MK7 | 2019 | Nueva generación: motor sin núcleo, reversa, cables desmontables | Nueva, con garantía; más cara |

**Decisión sugerida (02/11/2026), a confirmar por Ana:** para mezclar con la mejor calidad, **un par de MK5 o MK6**
(la MK6 solo si el precio está cerca de la MK5: los cambios son menores). Para coleccionismo, una **MK2 temprana hecha en
Japón con caja y papeles**, o las ediciones limitadas (doradas de aniversario, la GAE de 2016), que son más para mirar que
para mezclar. Mejor de 220-240 V; si es de 100 V el restaurador la adapta (sirve para pelear precio).

**MK2 vs MK3 (investigado 02/11/2026, pedido de Ana).** Nunca se recomendó evitar la MK3: solo se avisó lo del voltaje
(son japonesas, 100 V), y el restaurador de Ana las adapta, así que no es problema. Los vendedores confunden MK3, MK3D y M3D:
identificarlas por lo que tienen, no por el nombre del aviso. ¿El pitch hace clic en 0? Es MK2 o MK3. ¿Hay botón de reset y no
hay clic? Es MK3D o M3D. ¿RCA dorados de fábrica? Es japonesa (MK3 o MK3D). Mirar también la chapa de voltaje de abajo. **Fechar por número de serie:** el primer dígito es el último número del año (en los seriales nuevos, una letra A-L da el mes: A = enero). En una MK3 (fabricada de 1989 a ~1997) un 0 solo puede ser 1990. Para certeza, Panasonic informa mes y año si se le pasa el serial.

1200 = plateada, 1210 = negra: son la misma máquina. Las MK5G / M5G tienen
pitch de ±16 % y luces azules (la M3D no: es ±8 %). Están buenas pero no hacen falta.

- **Vista el 03/11/2026:** SL-1200MK3D plateada (dice "MK3D" en la chapa), con tapa
  acrílica y slipmat, a **ARS 2,2 M** una unidad. En el rango de una MK2: justo, no
  ganga. Si es de 100 V, usarlo para pelear el precio (el restaurador la adapta, no
  es impedimento). Preguntar: foto de la etiqueta de abajo (voltaje y serial), si
  incluye cápsula, service hecho, estado del pitch y del brazo.

### ¿Tienen que ser iguales? (pregunta de Ana, 02/11/2026)

No es obligatorio. Ana quiere mezclar con Seba o un amigo, cada uno con su bandeja, y eso se puede. Lo que tiene que
tener **cada** bandeja: control de pitch (±8 % alcanza), tracción directa con buen torque (que arranque rápido y que
se pueda frenar el plato con la mano), velocidad estable y **brazo manual** (las automáticas como la SL-D3 levantan o
vuelven el brazo solas y no van). Mezclar con bandejas distintas es más difícil al principio: el pitch tiene otra
escala y otro tacto, y el arranque o el frenado se sienten distintos. El par igual es más cómodo para aprender y es lo
estándar en clubes. Las diferencias de volumen entre cápsulas se emparejan con la ganancia (trim) del mixer.
Bandejas de otras marcas que cumplen: Pioneer PLX-1000, Reloop RP-7000 MK2, Audio-Technica AT-LP140XP.

### Qué revisar al comprar una usada (en Argentina, 220 V / 50 Hz)

- **Decisión de Ana (03/11/2026): fabricada en Japón sí o sí.** Vale para
  cualquier mercado: las de exportación hechas en Japón (220-240 V, chapa "M3D",
  MK2 europeas, etc.) también sirven. Lo que no quiere es que esté fabricada en
  otro país (vio MK5 que dicen Malasia). Pedir siempre foto de la etiqueta de
  abajo y buscar "Made in Japan"; ni el nombre de la chapa ni el voltaje alcanzan.

- **Voltaje:** ideal europea o de 220–240 V. Las japonesas (100 V) y las de
  EE.UU. (120 V) no son impedimento: el restaurador de Ana las adapta. Sirve
  para pelear el precio.
- **Estroboscopio:** las de 60 Hz (EE.UU. y Japón este) muestran mal los
  puntos con la red de 50 Hz. La velocidad está bien (va por cuarzo), pero
  la referencia visual queda engañosa.
- **Brazo:** que no tenga juego en los rulemanes (moverlo suave de arriba
  abajo y de costado).
- **Pitch:** que en 0 quede clavada en velocidad y que el fader no raspe.
- **Motor y eje:** que arranque con torque, que el plato no baile y que el
  eje no esté doblado.
- **Otros:** que no falte la tapa del plato ni el contrapeso, que el
  headshell esté bien y que las patas regulen.
- **Bueno:** número de serie legible y que las dos del par sean del mismo
  modelo.

### Precio de referencia MK2 usada en Argentina (consultado 2026-09-27)

- Estimación (sin datos en vivo, porque MercadoLibre y las cotizaciones
  estaban bloqueadas desde el sandbox): **US$ 700–1.000 por unidad**
  revisada y funcionando, **US$ 1.400–2.000 el par**. Afuera ronda
  US$ 500–800 por unidad. En Argentina sale más por la importación.
- Lo que se vio en ML ese día: publicaciones de ARS 1,87 M a 2,5 M
  (la de ARS 4 M probablemente sea un par). Falta chequear si son por
  unidad o por par.
- Con restaurador propio conviene mirar las "para reparar" y las que
  están sin service. Pagar menos y restaurar.

### MK2 como patrimonio: valor desde 1979 (consultado 2026-10-27)

- Lanzamiento 1979: ~990 DM (~€506, hifi-wiki), unos €1.300 de hoy. Nueva en UK
  1989 ~£300 y en USA 1997-98 ~US$450 (recuerdos de foros, no verificados).
- Hoy, usada: mediana €755 en Europa (HifiShark, 687 publicaciones), US$600-900
  en USA. Argentina: ARS 1,87-2,5 M (ML, sept. 2026), 50-70 % arriba de afuera.
- Lectura: el que la compró nueva perdió valor real. Desde que se discontinuó
  (2010), el usado sube por encima de la inflación. El techo lo pone la MK7 nueva.
  Riesgo local: el sobreprecio argentino. Comprar "para reparar" + restaurador
  protege mejor el valor.
- Falta: ventas cerradas (eBay sold) y una serie de precios año por año.

### Para qué sirve cada equipo (10/11/2026)

Regla: **"La bandeja lee, el mixer junta, el amplificador empuja, los bafles suenan."** El K.O. es un instrumento: hace
sonidos y entra al mixer como una bandeja más.

| Equipo | Qué hace | Analogía | ¿Lo tiene? |
|---|---|---|---|
| Bandeja + cápsula | Lee el surco | La aguja "lee" el disco | Sí: SL-1700 MK2 con Sumiko Pearl |
| Pre de phono | Sube la señal chiquita de la cápsula | Un megáfono para la aguja | Sí, adentro del Lenco (PHONO) y adentro de todo mixer DJ |
| **Mixer DJ** (mezcladora) | Junta 2 o más fuentes, pasa de una a otra (crossfader) y deja escuchar la próxima por auriculares (cue) | La mesa donde se encuentran dos discos | No: es lo próximo |
| Sampler (K.O. II) | Graba pedacitos y los toca en loop | Una caja de recortes de discos | Sí |
| Amplificador (Lenco A600) | Le da potencia a la señal para mover los bafles | El motor | Sí |
| Bafles | Convierten la señal en sonido | La boca | Sí (Technics) |
| Auriculares cerrados | Escuchar el próximo disco sin que suene en la sala | Espiar el disco que viene | No: los AKG son semiabiertos |
| Cápsula DJ | Aguja redonda (esférica), robusta, para tocar el disco con la mano | Una púa "todo terreno" | No |
| Slipmat | Deja patinar el disco sobre el plato | Hielo bajo el disco | No |
| 2.ª bandeja manual | Para mezclar disco con disco | La compañera de la 1700 | No (más adelante) |

**Cómo se conecta con un mixer:** bandeja → entrada PHONO del mixer; K.O. → entrada LINE del mixer; salida MASTER del
mixer → **AUX** del Lenco. La bandeja deja de ir al PHONO del Lenco.

**Cápsulas:** la Sumiko Pearl es ideal para **escuchar** y sirve para mezclar suave (Ana lo confirmó con alguien que sabe); para scratch y backcue, no. Para **tocar**, una
cápsula DJ esférica en su propio headshell. Ejemplos: Ortofon Concorde MkII (Club o DJ), Ortofon OM/Pro S en headshell,
Audio-Technica AT-XP3 o AT-XP5, Shure M44-7 usada.

**Mixers de 2 canales con phono (ejemplos):** Pioneer DJM-250MK2, Allen & Heath Xone:23, Reloop o Numark de entrada.
Usado vintage: Technics SH-DJ1200, Vestax PMC. Requisito: **dos entradas PHONO**, crossfader y salida de auriculares.

### Mixer en la mira: Pacson (investigado 10/11/2026)

**Rotary vs palancas.** El rotary (perillas, casi siempre sin crossfader) nació en las discotecas de los 70 (Bozak,
después UREI 1620, que usaban en clubes como el Paradise Garage) y es el preferido para house, disco y mezclas largas.
El de palancas (faders + crossfader) nació con el hip-hop para cortar rápido y scratchear; es el estándar de clubes
(Pioneer) y de los tutoriales. Que sea rotary no hace que suene mejor: el sonido depende del circuito (RBMA). Lo que
cambia es el gesto: girar es más fácil para subir despacio. **Isolator:** ecualizador de 3 bandas sobre el master que
puede cortar del todo cada banda. No todos los mixers lo tienen: es típico de los rotary; también existe suelto (Pacson
Iso3dj, E&S, MasterSounds).

**Pacson.** Marca argentina; en los 70-80 hacía amplificadores (recuerdos en forosdeelectronica, sin fuentes formales).
Sigue activa: vende por MercadoLibre e Instagram (@pacsonaudio). No se encontró fecha de fundación, fundador ni sitio
oficial. Modelos vistos:

| Modelo | Qué es | Datos |
|---|---|---|
| **PM-3AL** | Rotary de 3 canales con isolator | Ver ficha completa abajo. Ediciones negra y roja ("limited red"), vúmetros de aguja o LED. **Sin garantía.** Sin precio publicado. |
| **PM-2AL** | Rotary de 2 canales | 2 entradas phono, 4 de línea con A/B, vúmetros de aguja o LED. Avisos en ML de ARS 100.000 a 795.000 según la fecha; uno de Marketplace con nuevos a ARS 690.000. |
| **Iso3dj** | Isolator suelto | Avisos en ML desde ARS 49.500 (usado) hasta ~ARS 500.000. |

Sin reseñas independientes ni mediciones de Pacson (solo notas promocionales y avisos).

**Comparables de afuera (rotary):** Omnitronic TRM-202 MK3 (el más barato del mercado), Ecler WARM2, Union Audio
Orbit.2 LE (~US$ 930), Condesa Carmen V (~US$ 1.620), E&S DJR-400 (~US$ 2.000, hecho a mano), MasterSounds Radius,
Isonoe, Rane MP2015 (~US$ 3.200 usado). **De palancas para empezar:** Pioneer DJM-250MK2 (~ARS 1.000.000 en Frávega,
2026; €449 en Alemania), Allen & Heath Xone:23, Numark M2.

**Ficha oficial del PM-3AL (la pasó el vendedor de Pacson a Ana, 10/11/2026; Ana lo conoce y puede probarlo en persona):**
- Canales 1 y 2: entrada phono (47 kΩ, 5 mV) y de línea (100 kΩ, 450 mV), ganancia ±50 %, tonos de 3 bandas
  (graves +14/−26 dB, medios +14/−14 dB, agudos +14/−26 dB), envío y retorno de efectos, botón PFL (cue).
- Canal 3: línea **mono** (47 kΩ) y micrófono con low cut.
- Isolator de 3 bandas al master: +9/−45 dB cada una (corte casi total).
- Auriculares: perilla Cue/Mixing, salida de 1 W por canal. Vúmetro PFL, master L y R.
- Salidas: master RCA y XLR (−6 dB), rec (con isolator), booth (independiente).
- Eucalipto, 28,5 × 34,5 × 10 cm, 4 kg, 220 V 50 Hz, 5 W. **Sin garantía.**

Lectura (Claude): cubre todo lo que Ana necesita. La Pearl (4 mV) y la Concorde entran bien en el phono (5 mV, 47 kΩ).
Tiene cue completo, booth para el evento con Seba y rec para grabar. El K.O. en el canal 3 suena en mono; en estéreo va
en la entrada de línea del 1 o el 2. Faltan datos de ruido y distorsión, y no tiene garantía: probarlo en persona y que
lo revise el restaurador.

**Pendiente de preguntar a Pacson:** precio de cada edición; diferencia entre la negra y la roja; quién hace el service
si falla; si se puede probar en persona; si hay devolución. Para conectarlo: MASTER RCA → AUX del Lenco.

### SL-1700 MK2: coleccionable y voltaje (10/11/2026)

Regla: **"Original y reversible."** Lo que le da valor de colección es que esté completa y original (tapa, contrapeso,
headshell, chapa, cápsula original si está). Pasos para el voltaje:
1. Mirar la chapa de abajo: voltaje y si dice algo como "voltage selector".
2. Si tiene selector, el restaurador lo pasa a 220 V moviéndolo: no cambia nada original.
3. Si no tiene, el restaurador cambia el transformador interno y **guarda el original** en una bolsita con la bandeja.
4. Mientras tanto, el trafo externo va perfecto.

### SL-1700 MK2: valor (consultado 10/11/2026)

- Precio original en Alemania: 890 DM (hifi-wiki, sitio alemán). Casi lo mismo que una SL-1200 MK2 (990 DM): gama
  media-alta de Technics. Hoy serían ~US$ 1.300-2.100 según cómo se ajuste la inflación (en euros o en dólares).
- Usada afuera (eBay, precios pedidos, no ventas cerradas): **US$ 300-400** funcionando, casi todas desde Japón, más
  US$ 70-100 de envío. Vale menos de la mitad que una 1200 MK2 (mediana €755): a la 1200 la empuja la demanda DJ.

### Pacson PM-3AL vs Pioneer DJM-250MK2 (10/11/2026)

Datos del DJM-250MK2: ficha oficial de pioneerdj.com. Precio: ~ARS 1.000.000 (Frávega, 2026).

| | Pacson PM-3AL | Pioneer DJM-250MK2 |
|---|---|---|
| Control | Perillas (rotary), sin crossfader | Palancas + crossfader Magvel |
| Por dentro | Analógico de punta a punta | Digital (DSP de 64 bits): convierte el disco a digital |
| Graves por canal | EQ de 3 bandas, graves hasta −26 dB | **Isolator de 3 bandas por canal con corte total** |
| Isolator al master | **Sí**, 3 bandas, −45 dB | No |
| Filtro por canal | No | **Sí** (Sound Color FX) |
| Grabar | Salida rec (a la Mac, con interfaz USB aparte) | **Placa de sonido USB incluida**: graba directo a la Mac |
| Booth | **Sí** | No figura en la ficha |
| Efectos externos | Envío y retorno por canal | No |
| Canales | 2 phono + línea mono + mic | 2 (phono/línea) + mic |
| Garantía | **No** (se puede probar en persona) | Sí (oficial) |
| Tutoriales | Pocos | Muchísimos: es el estándar |

Lectura (Claude): el **Pacson** es el que va con el sonido y el gesto que Ana busca (analógico, rotary, isolator al
master, madera, local). El **Pioneer** es el camino seguro: garantía, tutoriales, corte total de graves por canal,
filtro y grabación directa. Recomendación: Pacson si la prueba sale bien y el precio está por debajo del Pioneer;
Pioneer si prefiere garantía y aprender con tutoriales.

### El resto del set (pendiente de definir)

- Mixer de 2 canales.
- Cápsulas DJ ×2: **Ortofon Concorde** (decisión de Ana, 10/11/2026).
- Slipmats.
- Auriculares cerrados (los AKG son semiabiertos y a Ana le aprietan arriba de la cabeza y es sensible a la presión: **prioridad comodidad**, vincha ancha y acolchada).
  Recomendados (10/11/2026, pesos aproximados): **Beyerdynamic DT 770 Pro** (~250 g, almohadillas de pana alrededor
  de la oreja, presión suave; versión de 80 Ω o 32 Ω) o **Sony MDR-7506** (~230 g, livianos y baratos). Sennheiser
  HD 25 (~140 g, el clásico de cabina) es el más liviano pero aprieta y se apoya sobre la oreja. ATH-M50x (~285 g)
  aprieta al principio. Probarlos antes si se puede.


## Catálogo para pinchar

Proyecto paralelo al setup: marcar qué temas de cada disco son los fuertes
para pinchar.

- No usar la etiqueta "para fiesta" ni su emoji. Usar el alien 👽 (concepto
  "de otro planeta").
- La sensación de sonido se describe con partes del cuerpo humano, estilo
  lámina antigua de anatomía.

| Disco | Tema | Zona |
|---|---|---|
| Björk, *Debut* (UK, One Little Indian, TPLP31, 1993; copia de Seba) | 👽 "Violently Happy" | Pecho / caja torácica, por los bajos claros y profundos |

## Decisiones / compras

_(nada todavía)_
