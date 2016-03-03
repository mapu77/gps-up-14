> Nota preliminar: tots els comentaris de la plantilla són informatius i han de desaparéixer en la versió entregable

# SISTEMA NOM - ESPECIFICACIÓ DE REQUISITS DEL SOFTWARE #


> El propòsit del document d'especificació de requisits és presentar el detall dels requisits del sistema. És un document evolutiu, atès que el nombre i detall dels requisits creix a mida que s'avança en el projecte

> Donat el principi de "dirigit per casos d'ús", l'especificació funcional pendrà la forma d'una especificació per casos d'ús

> Recordem que els documents de visió i cas de negoci tindran força informació sobre el producte, que aquí no repetirem


## 1. ESPECIFICACIÓ FUNCIONAL ##

### 1.1. Diagrama de casos d'ús

> Diagrama UML clàssic. És important mantenir la consistència amb altres documents, per exemple els actors del diagrama han de ser un subconjunt de les parts interessades establertes al document de visió (i més coses...)

> Si creieu que us ajuda a la legibilitat, podeu agrupar casos d'ús similars en paquets

![](http://agilemodeling.com/images/style/useCaseOnlineShopping.gif)

> A més, per cada cas d'ús, una descripció d'una o dues línies (fins i tot si el nom és prou auto-explicatiu, pot no ser necessari)

#### Paquet de gestió clients
- Cas d'ús UC001: - *Alta negoci*:  
descripció

- Cas d'ús UC002: - *Baixa negoci*:  
descripció

- Cas d'ús UC003: - *Alta usuari*:  
descripció

- Cas d'ús UC004: - *Baixa usuari*:  
descripció

#### Paquet gestió comerç
- Cas d'ús UC005: - *Alta oferta*:  
descripció

- Cas d'ús UC006: - *Alta promoció*:  
descripció

- Cas d'ús UC007: - *Editar informació botiga*:  
descripció

- Cas d'ús UC008: - *Editar catàleg*:  
descripció

- Cas d'ús UC009: - *Alta client fidel*:  
descripció

#### Paquet útils usuari
- Cas d'ús UC010: - *Subscripció*:  
descripció

- Cas d'ús UC011: - *Llistar botigues*:  
descripció

- Cas d'ús UC0112: - *Afegir valoració*:  
descripció

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

##### Justificació

##### Font

##### Criteris de  validació

1. ID requis*Usabilitat*. El sistema ha de ser molt usable, és a dir, fàcil i intuïtiu per a qualsevol persona que vulgui utilitzar aquest servei. Per tant, la part visual/gràfica ha de ser una eina d'ajuda i testejada per una variada mostra d'usuaris per tal que sigui satisfactòria pels ciutadans.
2. *Eficiència*. En el nostre cas, no és el requisit més important, però la eficiència és un terme a tenir en compte sempre de cara a l'usuari.
3. *Portable*. Òbviament, com el sistema està fet per diferents Sistemes Operatius i resolucions de pantalla, haurà de ser portable.
4. *Mantenible*. Si volem que l'app sigui utilitzada durant mols anys, haurà de ser altament mantenible per facilitar el treball en un futur.
5. *Segur*. Com hem dit és una aplicació personal, per tant, la segureta és un requisit a tenir en compte.
