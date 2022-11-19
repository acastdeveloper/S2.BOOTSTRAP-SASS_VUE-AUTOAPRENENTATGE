# SPRINT 2 - MAQUETACIÓ 2

###### Sumari:

- Preparació teòrica.

- Tasca S2. Bootstrap i SASS.

-----

## PREPARACIÓ TEÒRICA

**Bootstrap** és un framework CSS creat pels creadors de Twitter i serveix per maquetar de forma responsive utilitzant la seva codificació i permet estalviar molt de temps. Hi ha altres frameworks CSS com Material Design, Tail, i altres. Twitter tiene 

[Documentació Oficial de Bootstrap 5.0]([Introduction · Bootstrap v5.0](https://getbootstrap.com/docs/5.0/getting-started/introduction/)).



Es proposen els següents ***materials didàctics d'accès públic***:

- W3SCHOOLS -BOOTSTRAP 5 TUTORIAL: [Bootstrap 5 Tutorial](https://www.w3schools.com/bootstrap5/)

- Videos a Youtube de ***Pablo Monteserín***: 
  
  - Curso de Bootstrap 5 - 2/3: [Curso de Boostrap 5 → 2/3 - YouTube](https://www.youtube.com/watch?v=j8Cy239V1JI)
  
  - Curso de Bootstrap 5 - 3/3:  [Componentes en Bootstrap 5 - Componentes → 3/3 - YouTube](https://www.youtube.com/watch?v=MCefFNqfBG4)

- Bluuweb - Fundamentos de Bootstrap 5 [ SASS INCLUIDO + GUÍA CON CÓDIGOS ]: [Curso: Fundamentos de Bootstrap 5 [ Sass incluido + Guía con códigos ] - YouTube](https://www.youtube.com/watch?v=1kNwZbRiVcQ)



I **SASS** és un precompilador de CSS que serveix per crear arxius CSS a partir d'arxius escrits en llenguatge SASS que és un superconjunt de CSS. La gràcia de SASS és que es poden automatitzar moltes coses com anidaments, crear variables, funcions, etc. Tot i així les darreres versions de CSS ja han incorporat de forma nadiua les variables i cada cop hi van incorporant més coses. 

***Materials didàctics d'accès públic proposats***: 

- Video a Youtube EDteam - Aprende SASS en 20 minutos: [Aprende Sass en 20 minutos - #EDtaller 139 - YouTube](https://www.youtube.com/watch?v=mHp2nr2kErs)

- Video a Youtube de FreeCodeCAmp.org - SASS TUTORIAL FOR BEGINNERS - CSS WITH SUPERPOWERS: [Sass Tutorial for Beginners - CSS With Superpowers - YouTube](https://www.youtube.com/watch?v=_a5j7KoflTs)

- CSS-TRICKS - SASS STYLE GUIDE: [Sass Style Guide | CSS-Tricks - CSS-Tricks](https://css-tricks.com/sass-style-guide/)

-----

## TASCA S2. BOOTSTRAP I SASS

### Objectius

- Instal·lar FrameWord Bootstrap.
- Diseny responsive.
- Maquetació amb el sistema 12 columnes de Bootstrap.
- Ajustar la maquetació a la mida de la pantalla.
- Treballar amb finestres modals.



Cal construir una landing page que s'hi sembli al disseny següent:

![](./recursos_s2/Diseño/desktop-design.jpg)

Has d'utilitzar **Bootstrap 5 i SASS** per a generar els teus estils CSS.

#### Indicacions per a Bootstrap:

- Fer servir sempre que es pugui els **components de Bootstrap**, com per exemple els botons, *cards*, *navs*, *tooltips*... això t'estalviarà temps i la teva web guanyarà consistència. Aquí tens els components Bootstrap **->[components accordion/](https://getbootstrap.com/docs/5.0/components/accordion/)**

- **No modifiquis mai** les classes dels arxius **originals de Bootstrap**!

- Posicionar els elements amb les classes de marges i paddings de Bootstrap. Per a projectes grans, aquesta pràctica simplifica molt els arxius CSS, a més que llegint l'HTML ja pots saber com està posicionat en poder veure les seves classes. Per saber més d' **-> [utilities spacing de Bootstrap](https://getbootstrap.com/docs/5.0/utilities/spacing/)**

- **Personalitzar el tema de Bootstrap** per defecte per a adaptar-ho als estils de la web que estàs creant mitjançant SASS. No fa falta crear classes noves, pots ajustar Bootstrap per a adaptar-ho a les teves necessitats: *paddings* per defecte, colors del tema, marges...  
Molt recomanable que vegis aquest vídeo curt de com modificar les variables per defecte que porta Bootstrap:

[Bootstrap 5 Crash Course Tutorial #19 - Customizing Bootstrap - YouTube](https://www.youtube.com/watch?v=nCX3QVl_PiI)



### Nivell 1

#### Exercici 1

En aquest exercici començarem per la part principal, que és el contingut que veuen els usuaris en entrar a la web:

![](./recursos_s2/Diseño/exercici1.jpg)

Per a això hauràs d'implementar:

- La **barra de navegació** superior fixa, utilitzant el component "navBar" de Bootstrap.

**->[Components navbar](https://getbootstrap.com/docs/5.0/components/navbar/)**

- El **contingut principa**l, fent servir el "grid responsive" que proporciona Bootstrap per dividir la pantalla en dues columnes, a l'esquerra com pots veure està l'eslògan, la descripció i els botons, i en la columna dreta la imatge.

**->[Grid system](https://getbootstrap.com/docs/5.0/layout/grid/)**



>  **Important**
> 
> Abans de començar a muntar la web, hauràs de veure el vídeo recomanat anteriorment, per a aprendre a instal·lar Bootstrap en el teu projecte fent servir el gestor de paquets npm.

##### Requisits mínims:

- Instal·lar Bootstrap al projecte, no fer servir cdn (que és càrrega mitjançant per link, com per exemple "<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/...." rel="stylesheet" crossorigin="anonymous">").

- Fer servir component navBar de Bootstrap.

- Fer servir Grid Responsive de Bootstrap, ja que s'ha de veure bé en tauleta i mòbil.

- Modificar amb SASS, mitjançant l'arxiu creat per tu "main.scss", el color principal i secundari de Bootstrap. Utilitza aquestes variables pels color dels botons  

- Color principal: #5265E1

- Color secundari: #FA5959.

#### Exercici 2

Ara toca crear la part de funcionalitats del producte que estem venent:

![](./recursos_s2/Diseño/exercici2.jpg)

##### Requisits mínims:

- L'apartat "Features", amb el text descriptiu, ha d'anar dins del **Grid de Boostrap**.

- Has d'utilitzar el **component tabs** de Bootstrap, modificant els seus estils per adaptar-los a la nostra web

> **Per saber més**
> 
> En aquest tutorial ensenya com fer-ho.**-> [How to Style Bootstrap Tabs Step-by-Step](https://turbofuture.com/computers/Apply-custom-styles-to-bootastrap-tabs-step-by-step)**

-  Responsive.

#### Exercici 3

Has de construir la tercera part de la web: l'àrea de descàrregues:

![](./recursos_s2/Diseño/exercici3.jpg)

Com les cards de la imatge són molt diferents a les cards de Bootstrap, en aquest exercici et donem la possibilitat de, o bé personalitzar les cards de Bootstrap o bé crear les teves pròpies classes per maquetar-les.

##### Requisits mínims:

- Responsive.

- Botons de Bootstrap de color primary definit en l'exercici 1.



#### Exercici 4

ENHORABONA! Ja gairebé tens el nivell 1 completat! Ara toca desenvolupar l'apartat de FAQS:

![](./recursos_s2/Diseño//exercici4.jpg)

##### Requisits mínims

- Fer servir el component "Accordion" i personalitzar les classes per a adaptar-lo al disseny.

- Responsive.

- Botó de Bootstrap.



### Nivell 2

COMPTE! **abans de passar al nivell 2 verifica que has entès bé tots els exercicis del nivell 1**. 

El nivell 2 i 3 són opcionals, l'important és aprendre els conceptes de cada sprint, si l'has copiat ràpid d'internet no té valor, ja que si passes així tots els sprints, hauràs treballat molt i après poc. 

En una entrevista tècnica en una empresa o en les proves de nivell de l'itinerari (després del sprint 5 i 9) es detecta molt ràpid aquests casos. No retardis el teu aprenentatge, **millor fer pocs exercicis bé que molts ràpids.**



#### Exercici 5

Només falta un bloc per acabar la web: el footer.

![](./recursos_s2/Diseño//exercici5.jpg)

##### Requisits mínims

- Fer servir els formularis de Bootstrap.

- Mostrar un **missatge d'error** quan el formulari del butlletí de notícies s'envia, i el camp d'entrada és buit o l'adreça de correu electrònic no està formatada correctament. S'ha de fer amb Bootstrap.

>  **Per saber més**
> 
> Sobre formularis de Bootstrap **->[forms overview](https://getbootstrap.com/docs/5.0/forms/overview/)**
> 
> Més informació de com validar formularis amb Bootstrap **->[aquí](https://www.w3schools.com/bootstrap5/bootstrap_form_validation.php)**



### Nivel 3

#### Exercici 6

Modificar els estats actius dels botons, links, tabs i avisos de la web, perquè quedin així quan es passi el cursor per sobre:

![](./recursos_s2/Diseño/desktop-active-states.jpg)

#### Exercici 7

Com has implementat el posicionament de les cards de descàrregues de l'exercici 3? Has creat una classe o id per a cada card?:

![](./recursos_s2/Diseño/exercici3.jpg)

Per pocs elements no suposa molta feina, però que passaria si tinguessis una web plena de cards, les quals vols estilitzar en funció de la seva posició?, hauries de crear massa classes!

En aquest exercici hauràs de posicionar les targetes de l'exercici 3 utilitzant **l'herència de SASS** conjuntament amb la **pseudo-classe nth-child** (en aquest cas podem utilitzar nth-child(1), nth-child(2) i nth-child(3) per simplificar l'exercici).



##### Recordatoris

- **És obligatori pujar tots els lliuraments almenys amb el nivell 1** al final de l'sprint per a poder passar al següent.

- Els **lliuraments es faran a ser possible el dimecres o dijous de la segona setmana de l'sprint.** 

- Com a molt tard el lliurament es farà el dilluns següent a la finalització de l'sprint, dia que comença el nou sprint.

- Si vols **avançar al següent sprint abans d'hora**, has de finalitzar els tres nivells de la tramesa.



##### Recursos

**IMPORTANT: En **-> [aquest link, tens els recursos](https://itacademy.barcelonactiva.cat/mod/folder/view.php?id=9447)** per a poder crear la web.**



#### Valoració

### Estat de la tramesa

Estat de la tramesaAquesta tasca no requereix que trameteu res en línia.Estat de la qualificacióSense qualificacióCriteris de qualificació

(Nivell 1): Exercici 1: Creació de la barra de navegació superior fixa (navBar) + contingut principal

|                                                                                             |                                                                                                                                |                                                                                                                                    |
| ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------- |
| El resultat no s'ajusta al mòdel de l'enunciat i/o no és totalment responsiu.<br><br>0punts | Encara que el codi és correcte amb un navegador d'una amplada determinada, la "versió" mòbil presenta problemes.<br><br>1punts | Creació correcta de la barra de navegació superior amb la posició fixa i tots els requisits responsives correctes.<br><br>1.5punts |

Exercici 2: Creació de l'apartat de "Features" amb els 3 botons + (taca blava de fons)

| No s'ha usat Bootstrap o el disseny no s'acosta al plantejat<br><br>0punts | O no s'ajusta al disseny o la implementació de Bootstrap és millorable<br><br>0.5punts | Implementació correcta, tant en l'estructura, responsive i funcionalitats.<br><br>1punts |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |

Exercici 3: Creació de les 3 cards de l'apartat "Download"

| No s'ha usat Bootstrap o el disseny no s'acosta al plantejat<br><br>0punts | O no s'ajusta al disseny o la implementació de Boostrap és millorable<br><br>0.5punts | S'ajusta al disseny i s'ha usat correctament Boostrap<br><br>1punts |
| -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |

Exercici 4: Creació de l'apartat "FAQ" utilitzant el component "Accordion" (amb la funcionalitats del desplegament del contingut activat)

| No s'ha usat Bootstrap o el disseny no s'acosta al plantejat<br><br>0punts | O no s'ajusta al disseny o la implementació de Bootstrap és millorable<br><br>0.5punts | S'ajusta al disseny i s'ha usat correctament Boostrap<br><br>1punts |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |

El responsive és correcte en l'estructura general de tota la pàgina

| La pàgina no és responsive (no es mostra correctament en totes les resolucions)<br><br>0punts | Existeixen petits desajustaments en diferents parts de la web.<br><br>0.5punts | S'ajusta al disseny i s'ha usat correctament Boostrap<br><br>1punts |
| --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------- |

(Nivell 2): Exercici 5: Creació del footer utilitzant els formularis de BootStrap. amb autovalidació del camp de l'adreça quan estigui buida o sense el format correcte.

| No s'ha usat Bootstrap o el disseny no s'acosta al plantejat<br><br>0punts | O no s'ajusta al disseny o la implementació de Bootstrap és millorable<br><br>0.75punts | S'usa Bootstrap per al formulari i es valida correctament<br><br>1.5punts |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |

(Nivell 3): Exercici 6: Modificació dels estats actius dels botons, links, tabs i avisos de la web (quan el cursor passi per sobre).

| L'exercici no compleix amb els requisits<br><br>0punts | Implementació dels estats actius millorable o amb errors.<br><br>1.5punts | Implementació correcta dels estats actius de tota la web.<br><br>2punts |
| ------------------------------------------------------ | ------------------------------------------------------------------------- | ----------------------------------------------------------------------- |

Exercici 7: Gestió de les cards (amb una class o un id per a cada card), utilitzant l'herència de SASS conjuntament amb la pseudo-classe nth-child

| L'exercici no compleix amb els requisits<br><br>0punts | Falten estats actius o no s'ha usat SASS per a definir-los<br><br>0.5punts | Estan tots els estats actius i s'ha usat SASS per a definir-los<br><br>1punts |
| ------------------------------------------------------ | -------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |


