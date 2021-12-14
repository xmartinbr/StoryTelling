# StoryTelling
Repositori on hi podem trobar un exemple d' storytelling utilitzant dades públiques de la Comunitat de Madrid. 

Utilitzarem dades referents a poblacions, densitats, superfícies, incidència de Covid i defuncions de tots els municipis e intentarem trobar alguna relació entre 2 municipis, el de renta major i el de renta menor, en quant a la incidència de Covid i defuncions.

Per aconseguir-ho hem utilitzat el software "Flourish Studio" amb llicència free que ens ha permès dissenyar i crear diferents visualitzacions i després ajuntar-les totes en una "story". Aquesta eina facilita la presentació de dades d' una forma atractiva pels usuaris, a més les feines realitzades poden ser insertades als llocs web. Per utilitzar-la no hem de passar per un procés d' instal-lació, ja que la podem utilitzar directament des d' un navegador i a més per fer-la servir no és necessari tenir coneixements en programació.

He volgut enfocar-ho mostrant 2 tipus de visualitzacions, d' una banda presentant informació general de la característica explicada en tots els municipis i a continuació la versió particular dels municipis indicats anteriorment, per tant he utilitzat 2 tipus de gràfics per la 1ª opció he escollit visualitzacions que presenten distribucions de les dades i per la 2ª, gràfics que permeten mostrar més clarament la comparació entre 2 items.

En quant a les dades, aquestes han estat obtingudes de la web "https://datos.comunidad.madrid/catalogo" on hi podem trobar una gran quantitat d' informació relacionada amb la Comunitat de Madrid. Aquestes dades poden ser utilitzades segons la normativa indicada per la llicència "Creative Commons Attribution" amb el criteri indicat per "open data".

El fitxer "Story.html", conté bàsicament una etiqueta "div" indicant la ruta de la nostra "story" als servidors d' aquesta plataforma i a continuació una crida a una llibreria que el que farà serà executar codi que permetrà veure la visualització creada.
 
S' ha intentat que aquesta story complís amb els següents principis:
  * Presentar la informació des de diferents punts de vista.
  * Presentar la informació amb diferents nivell de detall.
  * Permetre visualitzar comparacions de les dades.
  * Poder donar una explicació amb les dades.
 
En quant als colors he decidit escollir una paleta de tipus qualitativa per poder pintar diferents series de dades amb diversos colors quant apareguin als gràfics, per tant la paleta estarà formada per colors diferents tots ells amb la mateixa intensitat i tó. Com a la majoria de gràfics apareixen 2 series de dades utilitzarem 2 colors ben diferents per poder visualitzar bé allò que volem mostrar.

En quant al text he volgut diferenciar 2 casos:
 * Les dades escrites als eixos utilitzen colors pàl-lids, d' aquesta manera si hi trobem moltes dades en un eix no ens provoca molèstia observar-les
 * Les dades escrites fora del eixos utilitzen color més intensos, justament per remarcar allò que estan mostrant. Això ho trobarem als pop-us i als títols o selectors.
