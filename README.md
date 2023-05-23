# Process_Injection
Recursos para el TFG

Video CHEATS NIOH: https://youtu.be/QHDQjjvaEnI


En la actualidad a la mayoría de usuarios de videojuegos les suele interesar hacer trampas.
Esto es algo que puede verse en los diferentes mercados que están en auge, donde se paga
al programador por modificar el comportamiento de los procesos. El caso más habitual es
el de las plataformas como Wemod o Mrantifun.net, que no son más que entrenadores, es
decir, programas que modifican el juego ofreciendo ventajas al usuario que los utilice,
tanto simples procesos de almacenamiento de munición como funciones de teletransporte
o vida infinita.
Por ello, en este proyecto se ha investigado cómo emular dichos comportamientos
gracias a herramientas como Cheat Engine (CE). CE es un escáner de memoria en
Windows que permite aplicar ingeniería inversa para modificar el comportamiento de
un proceso del que no se dispone de código fuente. Permite escanear ubicaciones de
memoria modificando su contenido o comportamiento mediante inyección de código,
y además permite el escaneo con mapa de puntero a un nivel o multinivel. Gracias a
esta herramienta se puede implementar un trainer en un juego actual, estudiando cómo
maneja la memoria, qué tipos de datos utiliza para almacenar las variables y haciendo
uso de las regiones cueva, que son regiones de memoria no utilizadas por el desarrollador
y aprovechadas para inyectar código mediante instrucciones en ensamblador.

