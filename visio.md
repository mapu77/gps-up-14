> Nota preliminar: tots els comentaris de la plantilla són informatius i han de desaparéixer en la versió entregable

# BCN-Commerce - VISIÓ #


> El propòsit del document de visió és recollir, analitzar i definir necesitats i capacitats d'alt nivell del sistema objecte del projecte. Escolliu un nom per al sistema.


## 1. INTRODUCCIÓ ##

> Breu motivació i presentació del sistema. No hauria d'ocupar més de 250 paraules 
 
El sistema a construir vol apropar el comerç petit i de proximitat als ciutadans i a les noves tecnologies. Donar-los un espai de promoció i de publicitat per tal d'incentivar la seva economia i donar-se a conèixer al públic.  
De cara al usuari, informar-lo d'ofertes, promocions i notícies sobre els comerços a la ciutat de Barcelona.


## 2. EL PROBLEMA ##

> Descrivim el problema que volem resoldre amb èmfasi en el seu impacte (sobre persones, la societat, l'economia, ...)  

Donades les dificultats que els petits negocis presenten per donar-se a conèixer a causa de la immensa captació de clients de les grans superfícies, oferim un sistema que permetrà al comerç de proximitat superar aquestes barreres i promocionar-se.  
Els negocis rebràn un espai on publicar-se, on donar-se a conèixer i on gestionar la seva empresa.  
Per als ciutadans de Barcelona els oferim un racó d'informació on poder consultar ofertes i notícies en lo referent a les botigues o comerços del barri, sent un punt de referència i d'informació.  
En alguns districtes de Barcelona la vida de barri està en desús i aquest sistema pretèn incrementar-la de nou i fer florir la activitat econòmica tot donant una imatge de ciutat viva.  

## 3. PARTS INTERESSADES ##

> Descriviu totes les parts interessades en el sistema  

1. *Petits comerços*.  
Representa una part del principals interessats en l'aplicació.  
El seu paper en l'aplicació es publicitar-se en els seus espais i que proporcionar ofertes i promocions.  

2. *Ciutadà de Barcelona*.  
Respresenta l'altre part dels principals interessats en l'aplicació.  
La responsabilitat d'aquesta part recau en l'ús d'aquest sistema per informar-se i fidelitzar-se amb els negocis més pròxims.  

3. *Ajuntament de Barcelona*.  
La creació d'aquesta aplicació oferirà prestigi i bona imatge a l'ajuntament ja que és el propi departament de *smartcities* qui s'encarrega de la creació d'aquest sistema.  
Per un bon funcionament del sistema caldrà que l'Ajuntament de Barcelona doni suport als comerciants per usar aquest sistema, ja sigui suport orientatiu, suport legal, suport tecnològic...  

4. *Competència*.
Tots aquells que no formin part del sistema poden rebre un impacte econòmic i social important - ja siguin grans superfícies com petits comerços que no vulguin participar en el projecte -.  
No requereix cap responsabilitat per part d'ells per a què el sistema funcioni.  

## 4. EL PRODUCTE ##

> Aquesta secció descriu en alt nivell les capacitats del producte, supòsits de funcionament, dependències sobre altres sistemes, ...
  
El nostre producte consisteix en una aplicació mòbil, tant per a Android, IOS i Windows Phone. A més a més, comptarà amb el suport d'una pàgina web, útil sobretot pels comercials.
Pel que fa a les capacitats del producte, volem apropar el comerç de proximitat al món tecnològic per tal d'impulsar aquest sector, així com satisfer als ciutadans. Centrant-nos
en dues vessants; els comerciants i els ciutadans. Pel que fa als comerciants, serà una plataforma que els hi permetrà publicitar-se, anunciar ofertes i descomptes, donar opció als
ciutadans de fidelitzar-se a la seva botiga a canvi d'uns certs avantatges pel client.
Pel que fa al client, el sistema comptarà amb un bon sistema de filtratge, per tal d'escollir les botigues que més l'interessi, tant a nivell ubicacional com a nivell categorial.
També tindràn l'opció de subscriure's a una botiga i rebre notificacions cada cop que hi hagi noves notícies, així com valorar aspectes de la botiga.
Els supòsits de funcionament són un Smartphone amb un dels Sistemes Operatius esmentats abans i connexió a Internet. El sistema també tindrà dependències amb Google Maps i amb el 
servei d'emmagatzematge web.

### 4.1. Perspectiva del producte ###
> Descriviu de quin tipus de producte estem parlant: un sistema d'informació, una app per a mòbil, un servei, un subsistema integrat en un sistema més gran, ...

El producte que volem dissenyar és un sistema d'inforació que consisteix en una app per a mòbil, que anuncia serveis dels petits comerços de Barcelona. A més a més, tindrà una
pàgina web que fara més fàcil la publicitat dels comerciants, tot i que igualment contindrà totes les funcionalitats de l'app. 
 
> Resumiu la informació en un dibuix que esquematitzi l'arquitectura del sistema:

![](http://www.dittoditto.com/img/screenshots/soft-arch.gif)

### 4.2. Descripció del producte ###
> Enumereu molt breument les funcionalitats més importants (el detall estarà en altre document, el d'especificació):

1. *Esplai publicitari*. Tot petit comerç de Barcelona es podrà anunciar a l'app sempre que compleixi tots els requisits i condicions demanats per l'Ajuntament(ex. dónar opció als clients
de fidelitzar-se a canvi de descomptes).
2. *Servei d'ofertes i promocions*. Tots els comerços tindran l'opció d'anunciar les ofertes i promocions especials per tal d'informar als clients.
3. *Servei de catàleg*. El comerciant podrà exposar el catàleg dels seus productes o serveis a l'app de tal forma que el client pugui veure de qué es tracta aquell comerç.
4. *Servei fidelització*. Els usuaris podran fidelitzar-se a una botiga a canvi de rebre notificacions d'aquesta i així tenir algun descompte en alguna promoció.
5. *Categories*. L'app comptarà amb un filtratge per categories (sabates, roba, electrònica...) per tal de facilitar la búsqueda als clients.
6. *Servei de valoració*. Els clients podran valorar el tracte rebut o la qualitat dels productes.
7. *Servei de subscripció*. Els clients podran subscriure's a una categoria per tal de rebre notificacions sobre allò.
8. *Servei de login*. Per a poder fer servir l'app tant l'usuari com el comerciant tindran un servei de Log In, perquè l'app sigui individualitzada (subscripció, fidelització...).
 
### 4.3. Supòsits de funcionament ###
> Enumereu els supòsits per a què el producti satisfaci la seva funcionalitat:

1. *Connexió Internet*. Descripció 
2. *Smartphone, tablet o ordinador*. Descripció 
3. ...
 
### 4.4. Dependències sobre altres sistemes ###
> Enumereu les dependències del producte sobre altres sistemes software existents:

1. *Google Maps*. Descripció 
2. *Servei de emmagatzematge web*. Descripció 
3. ...
  
### 4.5. Altres requisits ###
> Aquí ens referim només als requisits no funcionals (usabilitat, eficiència, ...). Poseu els més importants amb una molt breu descripció:

1. *Usabilitat*. Descripció 
2. *Eficiència*. Descripció 
3. *Portable*.
4. *Mantenible*.
5. *Segur*.

## 5. RECURSOS ##

> Si heu usat webs, documents, articles, etc., per basar el vostre document, enumereu aquí les referències tal i com es mostra aquí sota. Des de la resta del document, cal referenciar l'estudi amb el seu ID entre claudàtors, "[*id*]"

[1] https://es.wikipedia.org/wiki/Requisito_no_funcional

[2] recurs 2

[3] ...
