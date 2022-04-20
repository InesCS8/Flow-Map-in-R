# Flow-Map-in-R

**1.	Defició cada tècnica de visualització de forma general**

- NOM DE LA TÈCNICA DE VISUALITZACIÓ: Flow map o mapa de flux.
- ORIGEN: L'enginyer Henry Drury Harness va publicar en 1838 el primer mapa de flux mostrant la quantitat de trànsit de càrrega per carretera i canals a Irlanda.
https://en.wikipedia.org/wiki/Flow_map#/media/File:Harness_Ireland_Railroad_Map_1838.png
- DESCRIPCIÓ FUNCIONAMENT: Flow Maps mostra geogràficament el moviment d'informació o objectes d'una ubicació a una altra i la seva quantitat. Normalment, els mapes de flux s'utilitzen per mostrar les dades de migració de persones, animals i productes. 
- EXEMPLES D'APLICACIÓ: https://www.anychart.com/products/anymap/gallery/Maps_Connectors/Top_Chinese_Exports_to_the_World.php

**2.	Descripció del tipus de dades**

- QUANTITATIVES/QUALITATIVES: S'utilitza una variable quantitativa. També es necesari dispondre de 2 ubicacions (origen i destí) 
- ESTRUCTURA DE LES DADES: L'estructura de les dades és similar a la següent

![image](https://user-images.githubusercontent.com/104026026/164274597-9b270452-0afa-4ee4-bfd3-91afe9aa2a95.png)
- LIMITACIONS QUANT A DADES(MIDA MAX. I MÍNIMA): No permet la representació de més d'una variable quantitativa. Es necesari dispondre de les coordenades de 2 punts (origen i destí)

**3.	REPRESENTACIÓ GRÁFICA**

Transport de mercaderies per carretera de vehicles espanyols (tones i tones-quilòmetre) ANY 2020. Relacions comunitat autònoma d'origen i comunitat autònoma de destinació.

Dataset -> https://apps.fomento.gob.es/BDOTLE/visorBDpop.aspx?i=281

Eina emprada per realitzar el gràfic -> https://www.r-project.org/

![Valencian Freight Road Transport](https://user-images.githubusercontent.com/104026026/164069604-d1d80295-8ba8-4e4b-bb94-0fe8a949feb4.svg)

**4.	Comentar breument la representació**

Les províncies més pròximes a la Comunitat Valenciana són les que més tones de mercaderies han rebut d'aquesta.




