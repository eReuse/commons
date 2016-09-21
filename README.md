Llicències i convenis de transferència de béns:

## Llicències Generals

 > Llicència d'àmbit general amb els principis, definicions i pactes d'àmbit general entre els grups d'interès. Els acords específics entre els grups d'interès s'inclouran preferentment en les llicències derivades. 

#### (GCL) Llicència General d'un Circuit de Dispositius:

> Llicència d'àmbit general en el àmbit dels dispositius digitals  
> Estat: en desenvolupament la versió 1.0  
> Enllaç: [General-Circuit-License_CA.md](https://github.com/eReuse/commons/blob/devel/0-GCL-General-Circuit-License/General-Circuit-License_CA.md)


#### (GDL) Llicència General de Dades

> Llicència d'àmbit general en el àmbit de les dades que es generen durant el cicle de vida dels dispositius que gestionen.  
> Estat: No iniciada  
> Enllaç: 

## Llicències de circuit

#### (CL) Llicències de circuit

Està composta de tres convenis:

 * I) el conveni de cessió de dispositius entre el donant i el gestor, i l'annex amb les especificitats del donant, 
 * II) el conveni de cessió de dispositius entre el gestor i el receptor, i
 * III) el conveni de gestió del circuit on es defineixen les normes de funcionament.

En un circuit participa més d'un donant i ténen voluntats diferents en referència a qui pot gestionar i reutilitzar els dispositius que donen, per ex: "el receptor només pot ser una entitat sense ànim de lucre", etc... cada donant defineix aquestes voluntats en un document annex al conveni I. 

![Image of Document schema License](./98-utils/img/DocumentLicenseSchema.png) 

El procés d'elaboració de la llicència d'un circuit consta d'unir els tres convenis.

Els convenis on intervenen els donants són el I, III i annex, els gestors en el I, II i III i annexos, els proveïdors el III i els receptors el II i III. 
  
##### (CL-I) Llicències de circuit  - I) Conveni de cessió entre donant i gestor <!-- EN: DEED-OF-ASSIGNMENT-OF-ASSETS-DONOR-TO-MANAGER -->

> Estat: en desenvolupament la versió 1.0  
> Enllaç: [CL-I-DEED-OF-ASSIGNMENT-OF-ASSETS-DONOR-TO-MANAGER](https://github.com/eReuse/commons/blob/devel/1-CL-Circuit-License/CL-I-DEED-OF-ASSIGNMENT-OF-ASSETS-DONOR-TO-MANAGER.md)

En aquest conveni el donant/cedent transfereixen les responsabilitats (ambientals, legals, ..) cap al gestor. Seria similar a un conveni de cessió de béns. El signen el donant i el gestor. Es signen per periodes d'anys o sense data d'extinció i les parts poden finalitzar-lo en qualsevol moment o una part excloures.

> Aquest conveni el signarien tots els donants que volen donar al circuit (Aquesta signatura es pot realitzar en el moment que expresen la voluntat de donar). 
> Si un donant vol incloure noves clàusules ho pot fer en un annex, sempre que una nova clàusula no invalidi les dels documents II i III.

##### (CL-II) Llicències de circuit  - II) Conveni de cessió entre gestor i receptor

Aquest conveni és idèntic al I, només cal intercanviar els rols. Assegurem que les responsabilitats transferides al gestor alhora es transfereixen al receptor. El signen el gestor i el receptor. Es signen per periodes d'anys o sense data d'extinció i sempre les parts poden finalitzar-lo o una part excloures.

> Aquest conveni el signarien tots els receptors que volen rebre del circuit (Aquesta signatura es pot realitzar en el moment que l'entitat presenta el primer projecte).  

##### (CL-III) Llicències de circuit  - III) Conveni de gestió entre totes les parts.

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

## How to create odt or docx file
1.  Select a License or derived license
2.  Download de md (Markdown) document.
3.  Substitute parameters (TODO: search and replace script).
4.  Conversion to odt, pdf and others. Install or user [Pandoc] online (http://pandoc.org/demos.html#examples) or use Markdown Edit program.

