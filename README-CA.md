Llicències i convenis de transferència de béns:

## Llicències Generals

 > Llicència d'àmbit general amb els principis, definicions i pactes d'àmbit general entre els grups d'interès. Els acords específics entre els grups d'interès s'inclouran preferentment en les llicències derivades. 

#### (GCL) Llicència General d'un Circuit de Dispositius:

> Llicència d'àmbit general en el àmbit dels dispositius digitals  
> Estat: en desenvolupament la versió 1.0  
> Enllaç: 

#### (GDL) Llicència General de Dades

> Llicència d'àmbit general en el àmbit de les dades que es generen durant el cicle de vida dels dispositius que gestionen.  
> Estat: No iniciada  
> Enllaç: 

## Llicències de circuit

#### (CL) Llicències de circuit

Llicència d'un circuit en concret on principalment intervenen donants, gestors, proveïdors i receptors. Està composta de tres convenis: I) el conveni de cessió de dispositius entre el donant i el gestor, II) el conveni de cessió de dispositius entre el gestor i el receptor (similar al I però intercanviant rols), i III) el conveni de gestió del circuit.  El conveni té apartats com: i) Els que hi intervenen, ii) El Manifest, i els III) pactes. El procés d'elaboració de la llicència consta d'unir els tres documents, i cada actor interve en un o altre. Els convenis on intervenen els donants són el I i III, els gestors el I,II i III, els proveïdors el III i els receptors el II i III.  

> En aquest repositori posarem diversos convenis i pactes tipo per tal de donar diversitat d'exemples.   
> Per exemple un pacte tipo podria ser "el receptor té obligació de retornar al gestor del circuit el dispositius", o "el gestor només pot ser una entitat sense ànim de lucre", etc...
  
##### (CL-I) Llicències de circuit  - I) Conveni de cessió entre donant i gestor <!-- EN: DEED-OF-ASSIGNMENT-OF-ASSETS-DONOR-TO-MANAGER -->

En aquest conveni el donant/cedent transfereixen les responsabilitats (ambientals, legals, ..) cap al gestor. Seria similar a un conveni de cessió de béns. El signen el donant i el gestor. Es signen per periodes d'anys o sense data d'extinció i sempre les parts poden finalitzar-lo o una part excloures.

> En el cas d'implementació d'un transferhub aquest conveni el signarien tots els donants que volen donar al circuit 

##### (CL-II) Llicències de circuit  - II) Conveni de cessió entre gestor i receptor <!-- EN: DEED-OF-ASSIGNMENT-OF-ASSETS-MANAGER-TO-RECEIVER -->

Aquest conveni és identic al I, només cal intercanviar els rols. Assegurem que les responsabilitats transferides al gestor alhora es transfereixen al receptor. El signen el gestor i el receptor. Es signen per periodes d'anys o sense data d'extinció i sempre les parts poden finalitzar-lo o una part excloures.

> En el cas d'implementació d'un transferhub aquest conveni el signarien tots els receptors que volen rebre del circuit (Aquesta signatura es pot realitzar en el moment que l'entitat presenta el primer projecte).  
>
> Si un transferhub reb equips de donants que usen diferents convenis tipus I comporta que el receptor també haura de signar el corresponent conveni tipus II per a poder rebre dels tots els donants. 

##### (CL-III) Llicències de circuit  - III) Conveni de gestió entre totes les parts. <!-- EN: DEED-OF-ASSIGNMENT-OF-ASSETS-ALL-PARTS -->

En aquest conveni posem tot allò que afecta a totes les parts i regula com resoldre situacions específiques o compromisos que poden variar durant la vigència del conveni del donant. Un pacte descrit en aquest conveni no pot desactivar un pacte descrit en els punts I i II. 

> En el cas d'implementació d'un transferhub aquest conveni el signarien els receptors en el moment de rebre el dispositius. Pot passar que un receptor tingui dispositius amb diferents pactes tipus III (i també tipus II). Per exemple suposem que un receptor rep d'un donant públic i de un refabricador, l'equip del doannt públic no el podrà vendre i en canvi si podrà vendre l'equip del refabricador. Aquests pactes (o restriccions) aniran relfexades a l'etiqueta o seran visibles via realitat aumentada al llegir-se el codi QR.

##### (DL) Llicències de Dades
> Les parts aporten dades a eReuse.org segons la tipologia i es defineixen almenys tres tipus de llicència segons el contingut de les dades aportades

##### DL.1 - Profit - Product and component: durability (technical and Hardware ID).
##### DL.2 - Planet - Device Traceability: DCP, transferred organization (not if is a final customer social or not social) and disposal.
##### DL.3 - People - Social Impact of reuse: social receivers and impact (only if receiver is agreed with this license).

TODO.
 * Definir llicència DL.1
 * Definir llicència DL.2
 * Definir llicència DL.3* 

#### (E1) Llicència derivada d'un circuit – No Comercial
* Hereta de G1, entre tots els grups
* Inclou voluntat del donant i altres restriccions
TODO: Actualitzar amb la darrera versió en base als darrers acords.
https://github.com/eReuse/commons/blob/master/DonorFrameworkAgreement_CA.md

####(E2) Llicència derivada d'un circuit – Comercial
* Similar a 3 pero inclou drets d'imatge.

## Guide
1.  Select a License or derived license
2.  Download de md (Markdown) document.
3.  Substitute parameters (TODO: search and replace script).
4.  Conversion to odt, pdf and others. Install or user [Pandoc] online (http://pandoc.org/demos.html#examples)

