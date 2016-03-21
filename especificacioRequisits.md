# Bcn-eCommerce - ESPECIFICACIÓ DE REQUISITS DEL SOFTWARE #

> El propòsit del document d'especificació de requisits és presentar el detall dels requisits del sistema. És un document evolutiu, atès que el nombre i detall dels requisits creix a mida que s'avança en el projecte

> Donat el principi de "dirigit per casos d'ús", l'especificació funcional pendrà la forma d'una especificació per casos d'ús

> Recordem que els documents de visió i cas de negoci tindran força informació sobre el producte, que aquí no repetirem


## 1. ESPECIFICACIÓ FUNCIONAL ##

### 1.1. Diagrama de casos d'ús

![Diagrama de casos d'ús](img/DiagramaCasosUs.png "Diagrama de casos d'ús")

#### Paquet d'altes i baixes
- Cas d'ús UC001: - *Alta comerç*
Fa referència a l'acció de donar-se d'alta (registrar-se) al sistema per part dels usuaris/comerciants.

- Cas d'ús UC002: - *Baixa comerç*
Fa referència a l'acció de donar-se de baixa del sistema per part dels usuaris/comerciants.

- Cas d'ús UC003: - *Alta usuari*
Fa referència a l'acció de donar-se d'alta (registrar-se) al sistema per part dels usuaris/ciutadans.

- Cas d'ús UC004: - *Baixa usuari*
Fa referència a l'acció de donar-se de baixa del sistema per part dels usuaris/ciutadans.

- Cas d'ús UC005: - *Alta oferta*
Fa referència a l'acció d'afegir una oferta nova al comerç actor

- Cas d'ús UC006: - *Baixa oferta*
Fa referència a l'acció d'eliminar una oferta existent del comerç actor.

- Cas d'ús UC007: - *Alta producte o servei*
Fa referència a l'acció d'afegir un producte o servei al catàleg del comerç actor.

- Cas d'ús UC008: - *Baixa producte o servei*
Fa referència a l'acció d'eliminar un producte o servei existent del catàleg del comerç actor.

#### Paquet d'edició
- Cas d'ús UC009: - *Editar informació comerç*
Fa referència a la modificació de la informació del comerç actor.
 
- Cas d'ús UC010: - *Editar informació usuari*
Fa referència a la modificació de la informació del usuari actor.

- Cas d'ús UC011: - *Editar oferta*
Fa referència a la modificiació de la informaciço d'una oferta existent en el sistema del comerç actor.

- Cas d'ús UC012: - *Editar producte o servei*
Fa referència a la modificació de les informació d'un producte o servei existent en el sistema del comerç actor.

#### Paquet de utilitats
- Cas d'ús UC013: - *Sol·licitar fidelització*
El client/ciutadà sol·licita a un comerç la possibilitat de convertir-se en "client fidel" del comerç
amb l'objectiu de rebre bonificacions en les transaccions habituals amb el comerç.

- Cas d'ús UC014: - *Confirmar fidelització*
El comerç confirma les sol·licituts pendents de fidelització del clients que consideri lleials al comerç.

- Cas d'ús UC015: - *Subscripció*
L'usuari/ciutadà es podra subscriure als comerços que desitgi per rebre informació i novetats d'aquests a través de
l'aplicació i/o del e-mail.

- Cas d'ús UC016: - *Cercar negoci per barri*
L'usuari/ciutadà podrà cercar els negocis segons el barri de la ciutat que desitgi, ordenats alfabèticament.
Aquest cas d'ús pot acumular-se amb els altres casos d'ús de cerca. Per exemple, l'usuari podrà cercar segons barri i categoria.

- Cas d'ús UC017: - *Cercar negoci per categoria*
L'usuari/ciutadà podrà cercar els negocis segons la categoria que ofereixi l'aplicatiu, ordenats alfabèticament.
Aquest cas d'ús pot acumular-se amb els altres casos d'ús de cerca. Per exemple, l'usuari podrà cercar segons barri i categoria.

- Cas d'ús UC018: - *Cercar negoci per proximitat*
L'usuari/ciutadà podrà cercar els negocis segons la posició en que es trobi i localitzar-ne els més propers, ordenats alfabèticament.
Aquest cas d'ús pot acumular-se amb els altres casos d'ús de cerca. Per exemple, l'usuari podrà cercar segons on es trobi i categoria.

- Cas d'ús UC019: - *Afegir valoració*
L'usuari podrà valorar els comerços a través d'una puntuació numèrica i podrà afegir comentaris que seran visibles
tant el comerç com els altres usuaris.

### 1.2. Descripció individual dels casos d'ús

> Un per un, es descriuen els casos d'ús introduïts a la subsecció 1.1. Com ja s'ha dit adalt, els casos d'ús s'aniran defining paulatinament

#### Cas d'ús UC001 - *nom* ####

> Descripció del primer cas d'ús. Si bé en una especificació "de veritat", escriuriem el curs rellevant d'esdeveniments, excepcions, etc., aquí ens conformem amb una descripció més "lleugera"

#### Cas d'ús UC002 - *nom* ####

> etc.

## 2. ESPECIFICACIÓ NO FUNCIONAL ##

> Descriure en més detall els requisits no funcionals que han sortit al document de visió, intentant fer-los el més quantificables possible. Basar-se en alguna plantilla d'especificació de requisits

### Usabilitat - NFR001
##### Descripció
Sistema fàcil i intuïtiu per a qualsevol persona que vulgui utilitzar-lo. Per tant, una part visual fàcil i intuitiva.
##### Justificació
Per a que una aplicació sigui usable, la gent que la vulgui utilitzar ha de saber utilitzar-la de forma ràpida i poder fer tot allò que vol sense perdre molt de temps clicant a botons per a trobar la opció que ell vol.
##### Font
Usuaris
##### Criteris de  validació
Els usuaris la puntuan bé i no rebem queixes de díficil de utilitzar o que no saben utilitzarla.  



### Eficiència - NFR002
##### Descripció
Sistema ràpid, que no trigui molt a fer els cassos d'ús.
##### Justificació
Un sistema lent pot provocar desesperació a l'usuari i que deixi de utilitzar la aplicació. 
##### Font
Usuaris
##### Criteris de  validació
Els usuaris la puntuan bé i no rebem queixes d'aplicació lenta.


### Portable - NFR003
##### Descripció
Sistema apte per a diferents Sistemes Operatius i resolucions de pantalla.
##### Justificació
Si es vol que el sistema tingui una aplicació i una pàgina web, obviament haurà de ser compatible amb diferents resolucions (mòvils, tablets, ordinadors) i diferents Sistemes Operatius (Android, IOS, Windows Phone...).
##### Font
Ajuntament
##### Criteris de  validació
Es pot utilitzar en totes les plataformes on s'ha definit que haurà de funcionar.


### Mantenible - NFR004
##### Descripció
Sistema que es pugui mantenir durant molts anys i poder-lo actualitzar còmodament.
##### Justificació
Ja que s'inverteix des de l'ajuntament en aquest sistema, es desitja que es pugui mantenir i actualitzar fàcilment i sense masses inversions.
##### Font
Ajuntament
##### Criteris de  validació
Segueix una sèrie de criteris que confirmin la independència entre classes (entre altres coses).


### Segur - NFR005
##### Descripció
Sistema que no es pugui entrar externament i agafar dades personals dels clients o comerços.
##### Justificació
Aquest sistema tindrà informació privada, per tant, s'ha de cuidar que aquestes dades estiguin segures.
##### Font
Ajuntament i Usuaris
##### Criteris de  validació
Contractar a experts en seguretat informàtica que probin la seguretat.
