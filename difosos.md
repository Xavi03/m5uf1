# #
## ##

Els llenguatges de programació més difosos són aquells que més es fan servir en cadascun dels diferents àmbits de la informàtica. 
En l’àmbit educatiu, per exemple, es considera un llenguatge de programació molt difós aquell que es fa servir a moltes universitats o centres educatius per a la docència de la iniciació a la programació.  
Els llenguatges de programació més difosos corresponents a diferents àmbits, a diferents tecnologies o a diferents tipus de programació tenen una sèrie de característiques en comú que són les que marquen les similituds entre tots ells.

###1.5.1 Característiques de la programació estructurada
La programació estructurada va ser desenvolupada pel neerlandès Edsger W. Dijkstra i es basa en el denominat teorema de l’estructura. Per això utilitza únicament tres estructures: seqüència, selecció i iteració, essent innecessari
l’ús de la instrucció o instruccions de transferència incondicional.
D’aquesta forma les característiques de la programació estructurada són la claredat,
el teorema de l’estructura i el disseny descendent.

####Claredat
Hi haurà d’haver prou informació al codi per tal que el programa pugui ser
entès i verificat: comentaris, noms de variables comprensibles i procediments
entenedors... Tot programa estructurat pot ser llegit des del principi a la fi sense
interrupcions en la seqüència normal de lectura.

####Teorema de l’estructura
Demostra que tot programa es pot escriure utilitzant únicament les tres estructures bàsiques de control:
#####• Seqüència: instruccions executades successivament, una darrere l’altra.

#####• Selecció:
La instrucció condicional amb doble alternativa, de la forma “si condició, llavors SentènciaA, sinó SentènciaB”.

#####• Iteració: el bucle condicional “mentre condició, fes SentènciaA”, que executa les instruccions repetidament mentre la condició es compleixi.

####Disseny descendent  
El disseny descendent és una tècnica que es basa en el concepte de “divideix i venceràs” per tal de resoldre un problema en l’àmbit de la programació. Es tracta de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un nivell més abstracte i finalitzant en un nivell de detall.

####Programació modular
Quan es parla de programació modular, ens referim a la divisió d’un programa en parts més manejables i independents. Una regla pràctica per aconseguir aquest propòsit és establir que cada segment del programa no excedeixi, en longitud, d’un pam de codificació.  
En la majoria de llenguatges, els mòduls es tradueixen a:  
• Procediments: són subprogrames que duen a terme una tasca determinada i retornen 0 o més d’un valor. S’utilitzen per estructurar un programa i millorar la seva claredat.
• Funcions: són subprogrames que duen a terme una determinada tasca i retornen un únic resultat o valor. S’utilitzen per crear operacions noves que no ofereix el llenguatge.

##1.5.2 Característiques de la programació orientada a objectes  
Un dels conceptes importants introduïts per la programació estructurada és l’abstracció de funcionalitats a través de funcions i procediments. Aquesta abstracció permet a un programador utilitzar una funció o procediment coneixent només què fa, però desconeixent el detall de com ho fa.  
Aquest fet, però, té diversos inconvenients:
• Les funcions i procediments comparteixen dades del programa, cosa que provoca que canvis en un d’ells afectin a la resta.
• Al moment de dissenyar una aplicació és molt difícil preveure detalladament quines funcions i procediments necessitarem.
• La reutilització del codi és difícil i acaba consistint a copiar i enganxar determinats trossos de codi, i retocar-los. Això és especialment habitual quan el codi no és modular.

***L’orientació a objectes*** és un paradigma de construcció de programes basat en una abstracció del món real.  

Un ***objecte*** és una combinació de dades i mètodes que ens permeten interactuar amb ell. En OO, doncs, els programes són conjunts d’objectes que interactuen entre ells a través de missatges.
