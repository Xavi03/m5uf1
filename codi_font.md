#UF1:Entorns de desenvolupament#

##1.2 Codi font, codi objecte i codi excutable: màquines virtuals##

El ***codi objecte*** és el codi font traduït a codi màquina, però aquest codi encara no pot ser executat per l’ordinador.

El ***codi executable*** és la traducció completa a codi màquina, duta a terme per l’enllaçador. 
El codi executable és interpretat directament per l’ordinador.

***L’ enllaçador*** és l’encarregat d’inserir al codi objecte les funcions de les llibreries que són necessàries per al programa i de dur a terme el procés de muntatge generant un arxiu executable.

Una ***llibreria*** és una col·lecció de codi predefinit que facilita la tasca del programador a l’hora de codificar un programa.

El concepte de màquina virtual sorgeix amb l’objectiu de facilitar el desenvolupament de compiladors que generen codi per a diferents processadors.
La compilació consta de dues fases:
• La primera parteix del codi font a un llenguatge intermedi obtenint un programa equivalent amb un menor nivell d’abstracció que l’original i que no pot ser directament executat.
• La segona fase tradueix el llenguatge intermedi a un llenguatge comprensible per la màquina.
