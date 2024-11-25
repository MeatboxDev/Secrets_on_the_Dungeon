# Secrets_on_the_Dungeon

## Introducción
Este es el documento de diseño de Secrets on the Dungeon. Videojuego de Pc diseñado para el game jam con tema “Secretos”, restricción de paleta de colores pequeña de 4 colores o menos, soporte para cheat mode y récords y puntajes para speedruns.

## Concepto de juego
- **Tema:** Secretos
- **Descripción breve:** Un juego de mazmorras y secretos con cofres ocultos y enemigos, estilo roguelike, con una paleta monocromática de grises y sistemas de puntuación.

## Características principales
- **Exploración de mazmorras:** La atmósfera de las mazmorras será oscura y misteriosa, incentivando al jugador a explorar cada rincón en busca de secretos y tesoros.
- **Planteamiento sencillo:** La historia mencionada es muy simple, una mera excusa para el desarrollo del juego pero lo suficientemente explícita para que el Jugador sienta que tiene un objetivo.
- **Ampliación:** Secrets on the Dungeon debe ser ampliable con nuevos niveles y enemigos de forma sencilla. El motor será todo lo independiente posible del contenido. De esta forma los artistas podrán generar nuevos niveles, habilidades o enemigos. El sistema de generación procedural permitirá añadir nuevos niveles, enemigos y habilidades sin modificar el núcleo del juego.
- **Diseño modular:**
  - **Niveles construidos a partir de piezas:** Los niveles se construirán a partir de una serie de piezas predefinidas (salas, pasillos, etc.) que se combinarán de forma aleatoria para crear niveles únicos.
  - **Facilidad de creación de contenido:** Los artistas y diseñadores podrán crear nuevas piezas y elementos de forma sencilla, lo que permitirá ampliar el juego con nuevos contenidos de forma constante.
  - **Reglas de Creación de Niveles:** Los niveles deben construirse con piezas predeterminadas de salas, pasillos y áreas de enemigos que puedan combinarse aleatoriamente.
  - **Formato de Nivel:** Cada nivel debe tener al menos una entrada, un área de combate, y una salida.
  - **Enemigos Básicos y Avanzados:** Los artistas pueden diseñar enemigos que puedan aparecer en niveles de dificultad creciente sin modificar la base del juego.

## Género
- **Dungeons:** El género de Dungeons (Mazmorras) se centra en la exploración de entornos subterráneos o cerrados, llenos de enemigos, trampas y tesoros. Los juegos de este género suelen tener una estructura de niveles o pisos que los jugadores deben superar.
- **Roguelike:** El género Roguelike se caracteriza por su alta dificultad, generación procedural de niveles y la muerte permanente del personaje (permadeath). Estos juegos suelen ofrecer una experiencia única en cada partida debido a la aleatoriedad de sus elementos.
- **Novela Visual:** Las Novelas Visuales son un género de videojuegos centrado en la narrativa y el desarrollo de la historia a través de diálogos y elecciones del jugador. Estos juegos suelen tener gráficos estáticos o animados y se enfocan en la interacción con personajes y la toma de decisiones.

## Propósito y público objetivo
- **Objetivo del juego:** Proveer una distracción rápida y simple, con una dificultad que pueda escalar significativamente.
- **Público Objetivo:** Fans de los roguelike y juegos retro pixel art.

## Jugabilidad
- **Mecánicas principales:**
  - **Exploración**
  - **Combate**
  - **Tipo de Enemigos:** Incluye tres categorías: evasivos (huyen o se esconden), defensivos (defienden su espacio), y agresivos (persiguen al protagonista).
  - **Dificultad progresiva:** Conforme el jugador sube niveles, se incrementará la velocidad o número de enemigos en cada sala.
  - **Resolución de puzzles**
  - **Tipos de Puzzles:** Los puzzles serán de tipo "activación de zonas" o "colección de ítems" para desbloquear una salida o acceso.
  - **Dinámicas de juego:**
    - **Cheat mode**
    - **Speed runs**

## Estilo visual
- **Estilo artístico:** Pixel art
- **Paleta de Colores:** Monocromática de grises

## Desarrollo de la Historia
- **Introducción:** El protagonista descubre el laberinto sellado en su lugar natal y decide aventurarse en su interior.
- **Encuentros Iniciales:** En los primeros niveles, el protagonista se encuentra con criaturas de la oscuridad como esqueletos, gárgolas, slimes, fantasmas y arañas. Estas criaturas no son hostiles; huyen cuando el imp intenta atacarlas y algunos incluso hablan.
- **Encuentros con Bestias Salvajes:** A medida que avanza, el protagonista encuentra bestias salvajes como topos, ratas y lobos. Estas criaturas pueden atacar si están en estado de locura o hambre, pero generalmente se alejan.
- **Encuentros con Enanos:** Los enanos consideran al protagonista un enemigo, pero no son agresivos. Prefieren defenderse y retroceder cuando lo ven. Solo atacan si el protagonista los ataca primero o intenta cruzar su territorio, el cual puede esquivar.
- **Encuentros con Elfos:** Los elfos son más agresivos y atacan directamente si el imp entra en su rango de ataque. Se mantienen alertas y atacan si el imp se acerca demasiado. También hay elfos oscuros que actúan como NPCs aliados en puntos específicos.
- **Encuentros con Humanos:** En los niveles superiores, el imp se encuentra con humanos que intentan atacar en cuanto lo ven. Es una lucha a muerte, y los humanos pueden perseguir al protagonista y agruparse. Un pequeño porcentaje de humanos ha vendido su alma a la oscuridad y tratarán al imp como un aliado temporal, pero si hay otros humanos cerca, también lo atacarán.
- **Revelación del Secreto:** Al final del laberinto, el imp descubre que en realidad ha estado ascendiendo y que la mazmorra es una prueba diseñada para confundir y desafiar a los intrusos. Al salir, se da cuenta de que es el primer demonio en mucho tiempo que ha llegado al mundo humano desde que este cambió.
- **Cinemática del Lado Humano:** Se muestra una cinemática desde la perspectiva de los humanos, revelando su sorpresa y alarma al ver al protagonista emerger.
- **Enfrentamiento Final:** El imp es atacado por el ejército humano y debe derrotarlos para poder escapar y regresar a su mundo.
- **Huida de Vuelta al Laberinto:** Después del enfrentamiento, se abre la posibilidad de que el imp huya de vuelta al laberinto. Esta sección puede incluir nuevos desafíos y enemigos, así como la oportunidad de descubrir más secretos y obtener recompensas adicionales.

## Personajes
- **Criaturas de la Oscuridad:** esqueletos, gárgolas y slimes que no son hostiles y huyen o hablan cuando se les ataca.
  - Esqueletos
  - Gárgolas
  - Slimes
- **Bestias Salvajes:** Topos, ratas y lobos que pueden atacar si están en estado de locura o hambre, pero generalmente se alejan.
  - Topos
  - Ratas
  - Lobos
- **Razas Inteligentes:** Enanos, elfos y humanos, cada uno con su propio comportamiento y nivel de agresividad.
  - Enanos
  - Elfos
  - Humanos

## Protagonista
- **Interacción entre elementos:**
  - **Interacción con NPCs:**
    - Diálogos
    - Misiones