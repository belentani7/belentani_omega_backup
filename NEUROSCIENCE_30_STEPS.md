# BELENTANI OMEGA v8.0 — 30 PASOS DE NEUROCIENCIA COGNITIVA
## Plan de Experiencia Inmersiva Basado en Percepcion Humana

---

## EJE 1: PROCESAMIENTO PREATENCIONAL (Pasos 1-5)
*El cerebro procesa color, movimiento y contraste ANTES de la conciencia. 200ms. Sin esfuerzo.*

### PASO 1: FOVEAL CAPTURE — Color Rojo como Stimulus Preatencional
- **Ciencia**: El rojo (#ff003c) activa la amigdala en 120ms. Es el color que el ojo humano detecta mas rapido en la periferia visual.
- **Implementacion**: Todo el paleta cromatica gira alrededor del rojo sangre. Nada de azul, nada de verde como acentos. Solo rojo como signal unico.
- **Efecto**: El cerebro clasifica "peligro/importancia" antes de que leas una sola palabra.

### PASO 2: ONSET TRANSIENTS — Animaciones de Entrada con Spike de Luminancia
- **Ciencia**: Los "onset transients" son picos bruscos de brillo que activan el colliculus superior (region del cervello que detecta movimiento).
- **Implementacion**: Cada elemento aparece con un flash rapido de opacidad (0 → 0.3 → 1 en 200ms) seguido de un glow que se desvanece.
- **Efecto**: Cada seccion "aparece" como si emergiera de la oscuridad. El cerebro no puede ignorarlo.

### PASO 3: POP-OUT EFFECT — Un Solo Elemento Rompe el Patron
- **Ciencia**: En un campo visual uniforme, un elemento que difiere en una dimension (color, tamano, orientacion) "salta" automaticamente sin esfuerzo atencional.
- **Implementacion**: En cada grid de cards, UNA card tiene un borde que pulsa (2px → 0px → 2px) mientras las demas son estaticas.
- **Efecto**: El ojo va directo a esa card. Sin decision consciente.

### PASO 4: MICROSACCADAS DE COLOR — Variacion Subtil del Rojo
- **Ciencia**: El ojo hace 2-3 microsaccadas por segundo. Si el estimulo visual varia sutilmente, la fija mas tiempo.
- **Implementacion**: El borde rojo de las cards varia entre #ff003c, #cc0030, #ff1a4d en un ciclo de 8 segundos. Imperceptible conscientemente.
- **Efecto**: El cerebro registra "hay algo aqui" y mantiene la fijacion visual 340ms mas largo.

### PASO 5: CONTRASTE DE BORDE — Gradiente de Atenccion
- **Ciencia**: Los bordes de alto contraste (blanco/negro) capturan atencion antes que los de bajo contraste.
- **Implementacion**: Los elementos criticos (botones, logos) tienen borde solido. Los secundarios tienen borde difuso. Los terciarios no tienen borde.
- **Efecto**: Jerarquia visual automatica. El cerebro sabe que es importante sin leer nada.

---

## EJE 2: PERCEPCION TEMPORAL Y RITMO (Pasos 6-10)
*El cerebro humano es un reloj que busca patron temporal. El ritmo crea prediccion. La prediccion crea placer.*

### PASO 6: BEAT SENSORIAL — Pulso Visual Sincronizado a 60 BPM
- **Ciencia**: El cerebro tiene un "pacemaker interno" que opera entre 0.5-3 Hz. A 60 BPM (1 Hz) esta en el rango de relajacion atencional.
- **Implementacion**: El pulso del `live-dot` y el `grain` overlay operan a exactamente 1000ms (60 BPM). Sincronizados.
- **Efecto**: El usuario entra en un estado de "alerta relajada". No es ni aburrido ni ansioso.

### PASO 7: STRETCHED TIME — Expansions Temporales en Narrativa
- **Ciencia**: Cuando el cerebro detecta patron temporal, un "rompimiento" del patron crea una distorsion temporal subjetiva (se siente mas largo).
- **Implementacion**: En la seccion JUDAS, las frases largas van apareciendo letra por letra (typewriter) a velocidad lenta (40ms/char).
- **Efecto**: El usuario percibe que el tiempo se expande. La narrativa se siente mas profunda.

### PASO 8: RHYTHMIC ENTRAINMENT — Scroll como Musica
- **Ciencia**: El "rhythmic entrainment" es la sincronizacion del ritmo cardiaco y cerebral con ritmos externos.
- **Implementacion**: Las transiciones entre secciones duran exactamente 800ms. Siempre. Creando un ritmo predecible de "scroll → transicion → reveal".
- **Efecto**: El cerebro se sincroniza con la cadencia de la web. Cada scroll se siente como "el siguiente compas".

### PASO 9: TEMPORAL BINDING WINDOW — Audio y Vision Juntos
- **Ciencia**: El cerebro une audio y vision si ocurren dentro de una ventana de 200ms. Despues de 200ms, se perciben como separados.
- **Implementacion**: Cuando un elemento visual aparece, un sonido sutil (click, whoosh) suena dentro de los 100ms.
- **Efecto**: El usuario percibe que la web "responde" a su presencia. Sensacion de agency.

### PASO 10: PACING — Alternancia Rapido/Lento
- **Ciencia**: La atencion humana tiene un ciclo de 90-120 minutos (ultradian rhythm). Dentro de ese ciclo, hay micro-ciclos de 20-30 segundos.
- **Implementacion**: Cada 3 secciones hay una "pausa visual" — una pantalla con solo el titulo y negro, sin elementos.
- **Efecto**: El cerebro procesa lo que acaba de ver. Evita la sobrecarga cognitiva.

---

## EJE 3: INTEGRACION MULTISENSORIAL (Pasos 11-15)
*El cerebro no procesa audio y vision por separado. Los fusiona. La suma es mayor que las partes.*

### PASO 11: MCGURK EFFECT — El Oido Influye en lo que VES
- **Ciencia**: El efecto McGurk demuestra que lo que escuchas cambia lo que ves. El audio modula la percepcion visual.
- **Implementacion**: Sonidos graves (sub-bass) acompanan elementos visuales oscuros. Sonidos agudos acompanan elementos brillantes.
- **Efecto**: Los tonos oscuros se "ven" mas profundos. Los tonos brillantes se "ven" mas cercanos.

### PASO 12: CROSS-MODAL FACILITATION — Sonido Refuerza Movimiento
- **Ciencia**: Un "whoosh" sincronizado con un movimiento visual hace que el movimiento se perciba 30% mas rapido.
- **Implementacion**: Cada transicion de seccion tiene un sonido de "air" que acompaña el slide visual.
- **Efecto**: Las transiciones se sienten fluidas, naturales, como respirar.

### PASO 13: VISUAL-VESTIBULAR CONFLICT — Simular Profundidad
- **Ciencia**: Cuando los ojos ven movimiento pero el oido interno no lo detecta, hay un conflicto que crea inmersion o mareo.
- **Implementacion**: El parallax en el scroll crea movimiento visual que el vestibulo no detecta. pero es SUTIL (max 15% de desplazamiento).
- **Efecto**: Sensacion de "estar dentro" sin mareo. Sweet spot de inmersion.

### PASO 14: AUDITORY SCENE ANALYSIS — Capas de Sonido
- **Ciencia**: El cerebro separa el "soundscape" en figuras (sonidos importantes) y fondo (ruido ambiental).
- **Implementacion**: 3 capas de audio: (1) Drone grave constante, (2) Clicks/interaccion, (3) Narrativa vocal.
- **Efecto**: El cerebro nunca se siente en "silencio incmodo". Siempre hay algo procesando.

### PASO 15: SPATIAL AUDIO CUE — Sonido como Indicador de Direccion
- **Ciencia**: El cerebro localiza sonidos en el espacio. Un sonido a la izquierda mueve la atencion a la izquierda.
- **Implementacion**: Si el cursor esta a la izquierda, los sonidos de interaccion tienen un leve pan a la izquierda.
- **Efecto**: El usuario siente que el sonido "viene" de donde esta mirando. Embodiment total.

---

## EJE 4: ESTADOS COGNITIVOS Y EMOCIONALES (Pasos 16-20)
*El cerebro no es un procesador. Es un generador de emociones. Las emociones guian la atencion.*

### PASO 16: DOPAMINE PREDICTION ERROR — Recompensa Inesperada
- **Ciencia**: El sistema dopaminergico responde mas fuertemente a RECOMPENSAS INESPERADAS que a esperadas.
- **Implementacion**: Cada 3-5 scroll events, un elemento visual aparece que no estaba en el "mapa mental" del usuario (un destello, una frase nueva).
- **Efecto**: El cerebro libera dopamina. "Hay mas cosas por descubrir". Addiction loop.

### PASO 17: CURIOSITY GAP — Informacion Incompleta
- **Ciencia**: El cerebro odia la incomplez. Cuando detecta un patron incompleto, genera ansiedad que solo se resuelve completandolo.
- **Implementacion**: La seccion JUDAS muestra frases cortadas: "El proyecto se detuvo..." sin explicar por que.
- **Efecto**: El usuario SCROLLA para resolver la tension. No puede parar.

### PASO 18: COGNITIVE DISSONANCE — Contraste Emocional
- **Ciencia**: Cuando dos emociones opuestas coexisten, el cerebro busca resolver la disonancia. Eso requiere atencion profunda.
- **Implementacion**: Belleza visual (gold, glow) + Dolor narrativo (traicion, purga). Lo hermoso contiene lo doloroso.
- **Efecto**: El usuario no puede clasificar la experiencia como "bonita" ni "triste". Se queda en un estado de tension-productiva.

### PASO 19: MERE EXPOSURE EFFECT — Repeticion con Variacion
- **Ciencia**: El cerebro desarrolla preferencia por estimulos que ha visto antes, pero solo si hay variacion sutil.
- **Implementacion**: El motif del hexagono aparece en las gemas, en el cursor, en los bordes de cards, en los icons. Siempre ligeramente diferente.
- **Efecto**: familiaridad sin aburrimiento. El cerebro dice "conozco esto" pero sigue explorando.

### PASO 20: FLOW STATE TRIGGER — Balance Desafio/Habilidad
- **Ciencia**: Csikszentmihalyi: el flow ocurre cuando el desafio iguala la habilidad. Muy facil = aburrimiento. Muy dificil = ansiedad.
- **Implementacion**: La web tiene "niveles": nivel 1 (superficial), nivel 2 (scroll profundo), nivel 3 (oracle chat), nivel 4 (vision studio). El usuario elige su profundidad.
- **Efecto**: El usuario siempre esta en su sweet spot cognitivo. Nunca se aburre ni se frustra.

---

## EJE 5: MEMORIA Y RETENCION (Pasos 21-25)
*El cerebro olvida el 70% en 24 horas. La clave es codificar durante el encoding.*

### PASO 21: SERIAL POSITION EFFECT — Primero y Ultimo se Recuerdan
- **Ciencia**: El efecto de posicion serial dice que el primer y ultimo item de una lista se recuerdan mejor.
- **Implementacion**: El primer elemento visual de cada seccion es el mas impactante. El ultimo es un "hook" que lleva a la siguiente.
- **Efecto**: Cada seccion queda "anclada" en la memoria por sus extremos.

### PASO 22: CHUNKING — Agrupar en 5
- **Ciencia**: Miller's Law: la memoria de trabajo solo procesa 7±2 items. Pero con "chunking" se puede ampliar.
- **Implementacion**: Los 5 elementos (Pedro, Marcos, Santos, Belentani, The Human) estan en grupos de 5. Las canciones en grupos de 3-4.
- **Efecto**: El cerebro procesa "5 elementos" como una unidad. No se siente abrumado.

### PASO 23: EMOTIONAL ENCODING — Lo Emocional se Recuerda
- **Ciencia**: La amigdala (emocion) modula el hipocampo (memoria). Los eventos con carga emocional se codifican 3x mas fuerte.
- **Implementacion**: Cada seccion tiene un "momento emocional" — una frase, una imagen, un sonido que genera reaccion.
- **Efecto**: El usuario recuerda la experiencia porque fue EMOCIONAL, no solo informativa.

### PASO 24: SPACING EFFECT — Separar la Informacion
- **Ciencia**: La repeticion espaciada es mas efectiva que la repeticion masiva para la memoria a largo plazo.
- **Implementacion**: Los mismos temas (traicion, redemption, frequency) reaparecen en secciones diferentes con angulos distintos.
- **Efecto**: El cerebro refuerza los conceptos sin fatiga.

### PASO 25: METHOD OF LOCI — Anclaje Espacial
- **Ciencia**: El metodo de los loci asocia informacion con ubicaciones espaciales. Es la forma mas antigua y efectiva de memorizar.
- **Implementacion**: Cada seccion tiene un "lugar" visual unico: HOME = cielo estrellado, ARTIST = retrato, MUSIC = ondas, JUDAS = desierto, VISION = laboratorio.
- **Efecto**: El usuario puede "recordar" la web como si fuera un lugar fisico que visito.

---

## EJE 6: ESTETICA NEURO (Pasos 26-30)
*El cerebro tiene preferencias esteticas innatas. La simetria, el contraste y la complejidad optima generan placer.*

### PASO 26: BILATERAL SYMMETRY — El Cerebro Ama la Simetria
- **Ciencia**: La corteza visual procesa simetria bilateral como "belleza" automaticamente. Es innato.
- **Implementacion**: La pagina central esta centrada. Los elementos laterales son equidistantes. El layout es simetrico en el eje Y.
- **Efecto**: Placer estetico pre-consciente. El usuario se siente "bien" sin saber por que.

### PASO 27: COMPLEJIDAD OPTIMA — Ni Muy Simple Ni Muy Compleja
- **Ciencia**: La corteza visual prefiere complejidad intermedia (Berlyne). Demasiado simple = aburrimiento. Demasiado complejo = rechazo.
- **Implementacion**: Cada seccion tiene exactamente 3-4 elementos visuales principales + 1 detalle sutil que se descubre despues.
- **Efecto**: El cerebro encuentra la complejidad "justa". Ni vacia ni saturada.

### PASO 28: FIGURE-GROUND — Separar Sujeto de Fondo
- **Ciencia**: El cerebro siempre busca separar "figura" (lo importante) de "ground" (lo fondo).
- **Implementacion**: Los elementos principales tienen glow/blur de fondo. Los fondos son oscuros y difusos. Separacion absoluta.
- **Efecto**: Nunca hay confusion visual. El cerebro sabe exactamente donde mirar.

### PASO 29: GESTALT CLOSURE — Completar lo Incompleto
- **Ciencia**: El cerebro tiende a completar figuras incompletas. Un circulo con un hueco se ve como circulo completo.
- **Implementacion**: Los clip-path de las cards estan "cortados" en las esquinas. El cerebro los percibe como formas completas.
- **Efecto**: Las formas se sienten "diseñadas", "intencionales". No accidentales.

### PASO 30: AESTHETIC JUDEX — El Momento Final
- **Ciencia**: El "peak-end rule" (Kahneman): las personas juzgan una experiencia por su momento mas intenso y su final.
- **Implementacion**: La ultima seccion (CONTACT) tiene el contraste mas alto de toda la web: fondo negro absoluto, texto rojo brillante, silencio visual total.
- **Efecto**: La experiencia queda codificada como "intensa y elegante". El usuario se va con esa impresion.

---

## RESUMEN: COMO SE APLICAN LOS 30 PASOS

| Eje | Pasos | Principio Cerebral | Resultado en la Web |
|-----|-------|--------------------|---------------------|
| Preatencional | 1-5 | Procesamiento automatico sin esfuerzo | Atrapa en 200ms |
| Temporal | 6-10 | Ritmo y prediccion | Crea flujo temporal |
| Multisensorial | 11-15 | Fusion audio-vision | Inmersion total |
| Emocional | 16-20 | Dopamina, curiosidad, flow | Engagement adictivo |
| Memoria | 21-25 | Codificacion profunda | Retencion a largo plazo |
| Neuroestetica | 26-30 | Placer visual innato | Experiencia "hermosa" |

---

## ORDEN DE IMPLEMENTACION RECOMENDADO

1. Primero: Pasos 1-5 (base visual)
2. Luego: Pasos 6-10 (ritmo temporal)
3. Despues: Pasos 11-15 (capa sensorial)
4. Luego: Pasos 16-20 (engagement emocional)
5. Despues: Pasos 21-25 (memoria)
6. Final: Pasos 26-30 (pulido neuroestetico)
