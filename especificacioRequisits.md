# Bcn-eCommerce - ESPECIFICACIÓ DE REQUISITS DEL SOFTWARE #

> El propòsit del document d'especificació de requisits és presentar el detall dels requisits del sistema. És un document evolutiu, atès que el nombre i detall dels requisits creix a mida que s'avança en el projecte

> Donat el principi de "dirigit per casos d'ús", l'especificació funcional pendrà la forma d'una especificació per casos d'ús

> Recordem que els documents de visió i cas de negoci tindran força informació sobre el producte, que aquí no repetirem


## 1. ESPECIFICACIÓ FUNCIONAL ##

### 1.1. Diagrama de casos d'ús

![Diagrama de casos d'ús](img/DiagramaCasosUs.png "Diagrama de casos d'ús")

#### Paquet de gestió del comerç
- Cas d'ús UC001: - *Afegir comerç*
Fa referència a l'acció de donar-se d'alta (registrar-se) al sistema per part dels usuaris/comerciants.

- Cas d'ús UC002: - *Eliminar comerç*
Fa referència a l'acció de donar-se de baixa del sistema per part dels usuaris/comerciants.

- Cas d'ús UC003: - *Editar informació comerç*
Fa referència a la modificació de la informació del comerç actor.

- Cas d'ús UC004: - *Afegir oferta*
Fa referència a l'acció d'afegir una oferta nova al comerç actor

- Cas d'ús UC005: - *Eliminar oferta*
Fa referència a l'acció d'eliminar una oferta existent del comerç actor.

- Cas d'ús UC006: - *Editar informació oferta*
Fa referència a la modificiació de la informaciço d'una oferta existent en el sistema del comerç actor.

- Cas d'ús UC007: - *Afegir producte o servei*
Fa referència a l'acció d'afegir un producte o servei al catàleg del comerç actor.

- Cas d'ús UC008: - *Eliminar producte o servei*
Fa referència a l'acció d'eliminar un producte o servei existent del catàleg del comerç actor.

- Cas d'ús UC009: - *Editar producte o servei*
Fa referència a la modificació de les informació d'un producte o servei existent en el sistema del comerç actor.

#### Paquet de gestió d'usuari
- Cas d'ús UC010: - *Afegir usuari*
Fa referència a l'acció de donar-se d'alta (registrar-se) al sistema per part dels usuaris/ciutadans.

- Cas d'ús UC011: - *Eliminar usuari*
Fa referència a l'acció de donar-se de baixa del sistema per part dels usuaris/ciutadans.

- Cas d'ús UC012: - *Editar informació usuari*
Fa referència a la modificació de la informació del usuari actor.

#### Paquet de útils
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

- Cas d'ús UC020: - *Eliminar valoració*
L'usuari podrà eliminar qualsevol valoració que hagi afegit prèviament a un comerç i deixarà de ser visible tant pel
comerç com pels altres usuaris.

- Cas d'ús UC021: - *Reportar valoració*
En cas que algun comentari d'una valoració contingui qualsevol mena de llenguatge ofensiu, degradant o discriminatori,
la valoració podrà ser reportada per a la seva futura eliminació.

### 1.2. Descripció individual dels casos d'ús

> Un per un, es descriuen els casos d'ús introduïts a la subsecció 1.1. Com ja s'ha dit adalt, els casos d'ús s'aniran defining paulatinament


#### Cas d'ús UC001 - *Afegir comerç* ####

El sistema mostra una llista amb els camps necessaris per donar d'alta un comerç (Nom, Direcció, Tipus, Horari, Telèfon) i altres d'optatius com una fotografia o la pàgina webb si en té.
A continuació es mira a la base de dades si aquest comerç compleix els requisits, si els compleix s'afegeix al sistema i es demana un usuari encarregat de mantenir aquest perfil.
Si no compleix els requisits, s'avisa de perquè no i es deixa modificar els camps introduits de forma errònia.

#### Cas d'ús UC002 - *Eliminar comerç* ####

El sistema mostra el/s comerç/os que l'usuari és administrador. 
A continuació s'escull el comerç que es desitja eliminar, el sistema mostra un missatge de confirmació i a continuació s'elimina del sistema.

#### Cas d'ús UC003 - *Editar informació comerç* ####

El sistema mostra el/s comerç/os que l'usuari és administrador. 
A continuació s'escull el comerç que es desitja editar.
Es mostran tots els camps que estan omplerts i els que estan buits però es poden omplir perquè son optatius.
Es permet modificar qualsevol d'aquests camps.
Quan l'usuari adminsitrador desitja modificar els canvis es clica al botó 'guardar' i es guarden els canvis.
Enviar avís als subscriptors.

#### Cas d'ús UC004 - *Afegir oferta* ####

El sistema mostra el/s comerç/os que l'usuari és administrador. 
A continuació s'escull el comerç que es desitja afegir oferta.
Es mostren els camps necessaris per a afegir una oferta (article, tipus (2x1,descompte, etc.), data fi oferta).
A continuació es mira a la base de dades si aquesta oferta compleix els requisits, si els compleix s'afegeix al sistema.
Si no compleix els requisits, s'avisa de perquè no i es deixa modificar els camps introduits de forma errònia.
Enviar avís als subscriptors.

#### Cas d'ús UC005 - *Eliminar oferta* ####

El sistema mostra el/s comerç/os que l'usuari és administrador. 
El sistema mostra la/les oferta/es que té el comerç. 
A continuació s'escull la oferta que es desitja eliminar, el sistema mostra un missatge de confirmació i a continuació s'elimina del sistema.
Enviar avís als subscriptors.

#### Cas d'ús UC006 - *Editar informació oferta* ####

El sistema mostra el/s comerç/os que l'usuari és administrador. 
A continuació s'escull el comerç que es desitja editar.
Es mostren totes les ofertes que hi ha actualment.
A continuació s'escull l'oferta que es desitja editar.
Es mostran tots els camps que estan omplerts i els que estan buits però es poden omplir perquè son optatius.
Es permet modificar qualsevol d'aquests camps.
Quan l'usuari adminsitrador desitja modificar els canvis es clica al botó 'guardar' i es guarden els canvis.
Enviar avís als subscriptors.

#### Cas d'ús UC007 - *Afegir producte o servei* ####

El sistema mostra el/s comerç/os que l'usuari és administrador. 
A continuació s'escull el comerç que es desitja afegir producte.
Es mostren els camps necessaris per a afegir un producte (article, preu).
A continuació es mira a la base de dades si aquesta oferta compleix els requisits, si els compleix s'afegeix al sistema.
Si no compleix els requisits, s'avisa de perquè no i es deixa modificar els camps introduits de forma errònia.
Enviar avís als subscriptors.

#### Cas d'ús UC008 - *Eliminar producte o servei* ####

El sistema mostra el/s comerç/os que l'usuari és administrador. 
El sistema mostra el/s producte/s que té el comerç. 
A continuació s'escull el producte que es desitja eliminar, el sistema mostra un missatge de confirmació i a continuació s'elimina del sistema.
Enviar avís als subscriptors.

#### Cas d'ús UC009 - *Editar producte o servei* ####

El sistema mostra el/s comerç/os que l'usuari és administrador. 
A continuació s'escull el comerç que es desitja editar.
Es mostren tots els productes que hi ha actualment.
A continuació s'escull el producte que es desitja editar.
Es mostran tots els camps que estan omplerts i els que estan buits però es poden omplir perquè son optatius.
Es permet modificar qualsevol d'aquests camps.
Quan l'usuari adminsitrador desitja modificar els canvis es clica al botó 'guardar' i es guarden els canvis.
Enviar avís als subscriptors.

#### Cas d'ús UC010 - *Afegir usuari* ####

Es mostren els camps necessaris per a afegir un usuari (nom, cognom, email, pseudònim) i altres camps optatius com una fotografia.
A continuació es mira a la base de dades si aquest usuari compleix els requisits, si els compleix s'afegeix al sistema.
Si no compleix els requisits, s'avisa de perquè no i es deixa modificar els camps introduits de forma errònia.

#### Cas d'ús UC011 - *Eliminar usuari* ####

L'usuari clica el botó eliminar, es mostra un missatge de confirmació i si s'accepta, s'limina l'usuari.

#### Cas d'ús UC012 - *Editar informació usuari* ####

Es mostran tots els camps que estan omplerts i els que estan buits però es poden omplir perquè son optatius.
Es permet modificar qualsevol d'aquests camps.
Quan l'usuari desitja modificar els canvis es clica al botó 'guardar' i es guarden els canvis.

#### Cas d'ús UC013 - *Sol·licitar fidelització* ####

L'usuari està a la pantalla d'un comerç.
Clica el botó de fidelitzar.
El sistema guarda la petició i envia un avís al administrador del comerç, que l'acceptarà o no.

#### Cas d'ús UC014 - *Confirmar fidelització* ####

L'usuari administrador del comerç rep un avís, quan l'obri, té dos opcions, acceptar-la o no.
Depenen de l'opció escollida l'usuari que fa la petició serà fidel o no.

#### Cas d'ús UC015 - *Subscripció* ####

L'usuari està a la pantalla d'un comerç.
Clica el botó de subscripció.
El sistema guarda la petició i cada cop que hi hagi una novetat rebrà un avís.


#### Cas d'ús UC016 - *Cercar negoci per barri* ####

L'usuari selecciona el barri d'una llista i es mostra una llista amb tots els negocis del sistema situats en aquest barri.

#### Cas d'ús UC017 - *Cercar negoci per categoria* ####

L'usuari selecciona la categoria d'una llista i es mostra una llista amb tots els negocis del sistema d'aquesta categoria.

#### Cas d'ús UC018 - *Cercar negoci per proximitat* ####

L'usuari accepta la petició de saber la seva posició actual.
El sistema mostrarà tots els comerços més pròxims i ordenats per la distància a la que estan de l'usuari.

#### Cas d'ús UC019 - *Afegir valoració* ####

L'usuari està a la pantalla d'un comerç.
Clica l'opció de valoracions.
Quan està al final de la vista escriu al requadre que hi ha i clica el botó enviar.
El sistema guarda la valoració i la afegeix a les valoracions del comerç.

#### Cas d'ús UC020 - *Eliminar valoració* ####

L'usuari està a la pantalla d'un comerç.
Clica l'opció de valoracions.
Quan selecciona una valoració seva i clica el botó eliminar el sistema esborra a les valoracions del comerç la seleccionada.

#### Cas d'ús UC021 - *Reportar valoració* ####

L'usuari està a la pantalla d'un comerç.
Clica l'opció de valoracions.
Selecciona una valoració i clica el botó reportar (perquè li sembla ofensiva). 
El sistema avisa als adminsitradors del sistema i si es cal, s'esborra a les valoracions del comerç el comentari seleccionat.

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
