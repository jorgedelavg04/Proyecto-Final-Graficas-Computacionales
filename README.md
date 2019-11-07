# Proyecto-Final-Graficas-Computacionales

Emilio Hernández López     
Jorge De la Vega Carrasco  
Naji Saadat

Requisitos Funcionales 

Para este proyecto utilizaremos la API Web Audio y utilizaremos el constructor Audio Analyser con el que es posible recibir datos sobre la frecuencia de una canción el cual consiste de enteros entre 0 y 255 que son guardados en un arreglo. 
El usuario podrá seleccionar la canción desde su computadora, debe ser un archivo mp3.

https://threejs.org/docs/#api/en/audio/AudioAnalyser

La figura que utilizaremos como modelo será una de las hechas por el profesor en clase la cual será un ave que se encuentra volando o bien alguna figura animada utilizando FBX. Mientras haya una canción la figura hará la animación de estar en movimiento y cambiará de movimiento conforme las frecuencias vayan alternándose, así como alrededor de ella habrá figuras especiales que tengan que ver con la música. 

Las frecuencias mostraran cambios en la figura y el espacio. El ave se moverá conforme avancen las frecuencias, elegiremos una frecuencia media (no muy alta ni baja) con la cual la figura cambiará de posición. En los alrededores aparecerán fuegos artificiales. La forma en la que se aplicará es utilizando un sistema de partículas junto con una esfera. El sistema de partículas disparará las partículas y la esfera se iluminará simulando el disparo de un fuego artificial: cuando la frecuencia sea alta se dispararon muchas partículas y se iluminará la esfera con luz muy alta, en el caso que la frecuencia sea baja disparará pocas partículas y la luz de la esfera no será alta. 


Conexión a Spotify con la música que está sonando en la plataforma. 

Fuegos artificiales -  Velocidad 
Ondas circulares - Line renderer cos y sin
Luces de colores - color frecuencia
