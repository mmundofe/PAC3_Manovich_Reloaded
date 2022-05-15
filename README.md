# PAC3: Visionant el futur amb les ulleres de Manovich

### Recurs d'aprenentatge de Cultura Digital 

Autor: Martí Mundó

Data: 15-maig-2022

![Cultura Digital](https://miro.medium.com/max/1400/0*9PyyNvrO2PcD3KuU.png) 

## Plantejament

Manovich, en el seu llibre *“Software Takes Command”*, exposa la hibridació del programari com el següent pas natural en l’evolució dels mitjans i la tecnologia digital. Després de la “**remediació**”, la simulació digital de mitjans físics “antics” ja existents (eg. diari → pàgina web), i de la **invenció de nous mitjans informàtics** “artificials” sense precedents físics (eg. l’hipertext), era d’esperar que comencessin a sorgir **combinacions d’aquests mitjans**, donant com a resultat un mitjà híbrid.

> *“Once computers became a comfortable home for a large number of simulated and new media, it is only logical to expect that they would start creating hybrids”* (Manovich, *“Software Takes Command”,* 2013).  

Així mateix, la hibridació **no és la simple convivència conjunta de diferents tipus de mitjans**, com una pàgina web o un PowerPoint on eventualment es combini text, imatge, vídeo…, ja que Manovich, basant-se en el principi general de la Gestalt *“el tot és més que la suma de les parts”,* estableix que la hibridació comporta una **fusió entre les parts**, oferint una **experiència nova**, diferent a la que s’experiemntaria per separat.

> *“different media forms and traditions, are brought together resulting in new media gestalts. That is, they merge together to offer a coherent new experience different from experiencing all the elements separately.”* (Manovich, *“Software Takes Command”,* 2013).

Per tant, la hibridació ha de comportar una nova manera de representar el món o la forma en com s'interactua amb aquestes representacions, oferint noves tècniques de navegació i d’interacció, nous formats de mitjans o ambdues coses a la vegada (Manovich, 2013). Però a mesura en què el **programari esdevé un servei entrellaçat** a qualsevol àmbit de la societat, la hibridació **sobrepassa les dimensions descrites per Manovich**, possibilitant la gènesi de noves experiències en forma de serveis com mai abans podien experimentar-se.

## Re-descobrint la hibridació 1: Live view in Google Maps

*Live view in Google Maps* és la definició que utilitza Google per a la nova experiència de navegació combinada amb la realitat augmentada (AR en les seves sigles en anglès).

Google Maps és, en la seva essència, un servei de cartografia digital, el que vindria a ser una “remediació” de la cartografía “tradicional” del món físic, que permet trobar ubicacions de llocs físics i determinar la manera d’arribar-hi, presentat per primera vegada l’any 2005 (Viquipèdia, 2021) en forma de servei online, és a dir, un programari en evolució contínua sobre el qual s’hi van afegint constantment millores, funcionalitats, capes d’informació, continguts, etc… que, a la vegada, hom pot utilitzar per crear les seves pròpies solucions en forma de nous serveis o nous híbrids ([Google Maps Platform](https://developers.google.com/maps)).

La realitat augmentada (AR) és el terme emprat per referir-se a la superposició d’informació i contingut digital en el món físic a temps real, com si ambdues coses estiguessin juntes en el mateix espai, de manera que amb aquest nou mitjà informàtic, es combina qualsevol mitjà digital amb el món físic real projectat en una pantalla a través d’una càmera. Per exemple, mentre apuntem amb una càmera a qualsevol lloc de l’espai físic que ens envolta, es poden superposar fotografies, vídeos, imatges generades en 3D, animacions, textes, etc… creant una realitat mixta a temps real sobre la pantalla en la qual s'estigui observant.

Google anomena *Live view in Google Maps* a la combinació de Google Maps amb la realitat augmentada, un servei que es va començar a provar l’any 2019 (Google AI Blog, 2019). La idea sorgeix com a solució a una doble problemàtica. Per una banda busca solucionar un problema tècnic relacionat amb la precisió del posicionament en entorns urbans amb una alta densitat d’edificis i, per una altra banda, busca solucionar un problema d’experiència d’usuari davant d’instruccions del tipus *“Ves en direcció sud-est per Carrer Torrent de l’Olla cap a Carrer Montseny”.*

El resultat final a nivell de front-end és la projecció simultània a temps real de la superposició del mapa bidimensional amb les imatges reals de l’entorn per on es desplaça l’usuari i les indicacions de la ruta mitjançant text i infografia 3D ajustant-se a la perspectiva de la càmera i la direcció de la ruta. Per a que això sigui possible, a nivell de back-end és necessari combinar altres tecnologies de Google, com [Visual Positioning Service](https://youtu.be/ogfYd705cRs?t=5128) (VPS), [Street View](https://www.google.com/streetview/) i Machine Learning, que s’encarreguen de processar la informació enviada pel dispositiu (GPS, brúixola i imatges), i obtenir el que Google anomena *global localization.*

Des del punt de vista que Manovich exposa a *“Software Takes Command”* (2013), estaríem davant d’una experiència nova d’hibridació que ja parteix d’una hibridació de mitjans, com és el cas de Google Maps, a la qual s’hi afegeixen les tecnologies Visual Positioning Service (VPS), Street View, Machine Learning i la capacitat de processament en el núvol per generar la informació necessària que permet construir un nou format de mitjà i noves tècniques d’interacció fruit de combinar Google Maps i la realitat augmentada (AR).

## Re-descobrint la hibridació 2: Cabify

Cabify és una empresa nascuda a Espanya l’any 2011 (Cabify, 2022) de *ride-sharing* que connecta usuaris amb una selecció de conductors privats a través d’una aplicació mòbil amb la finalitat de traslladar aquests usuaris des d’un punt d’origen fins a un punt de destí a canvi d’una compensació econòmica. A partir d’aquesta definició, es podria establir que el servei de Cabify tindria com a precedent el servei de transport públic de Taxi. 

En general, a Barcelona, el servei de transport de Taxi està format per un col·lectiu de professionals independents que poden estar agrupats en major o menor mesura però a nivell de compartir serveis complementaris. Quan un usuari té la necessitat d’utilitzar aquest servei públic de transport, generalment ho pot fer de dues maneres: aturar un taxi lliure que estigui circulant pel carrer o acudir a una parada de taxi i agafar el primer de la fila. 

Al llarg del temps, s’han anat afegint diferents canals complementaris per sol·licitar el servei, com el telèfon, les apps, etc, però de manera fragmentada i no compartida a nivell de servei de Taxi. El preu final que paga l’usuari serà variable com a resultat d’aplicar una tarifa regulada per l’autoritat del transport en funció de la distància recorreguda i el temps que s’ha trigat en recorre-la. 

Aquest és un sistema de funcionament que, en essència, no ha variat gaire des de que es va regular el servei per una autoritat del transport a Barcelona i, a nivell d'experiència, tampoc. Quan l’usuari es disposa a utilitzar aquest servei, aquest no té cap coneixement sobre on ni quant de temps trigará en trobar un taxi lliure, informació sobre el conductor, el tipus de taxi, el preu de la carrera, la ruta que farà, duració del trajecte, si es desvia de la ruta addient, l’idioma en el que pot comunicar-se i altres detalls del vehicle. 

Cabify funciona de manera que quan un usuari necessita un servei de transport de porta a porta, l’equivalent al servei de Taxi, aquest realitza una sol·licitud a través de l’app. L’app és un mitjà informàtic, unificat, amb dos extrems. Per una banda el de l'usuari que fa la petició del servei i, per l’altra, el del conjunt de conductors als quals se’ls hi assignen les peticions rebudes que, a través de la plataforma digital de Cabify, es processa tota la informació necessària per prestar el servei. 

El resultat final a nivell de front-end és que tant usuaris com conductors disposen d’una representació visual a l'ús d’un servei que fins aleshores, en el servei de Taxi, no existia.  Una representació que fusiona diferents mitjans, com cartografia digital, text, imatge, telefonia, GPS, etc… a través de la qual, els usuaris interactuen per visibilitzar el servei i tota la informació relacionada: disponibilitat, temps, preu, recorregut a temps real, etc…

Des del punt de vista de Manovich, l’app de Cabify podria ser un cas d’hibridació de mitjans “futur” portat al terreny de les apps de serveis, en tant en quant l’app actua com a nou mitjà per representar un servei a l’ús, el de Taxi, “remediat” i de manera diferent oferint una experiència del servei completament nova. 

### Referències i Bibliografia

* VV.AA. ***Realitat augmentada*** [en línia]. Viquipèdia, 8 de març de 2022. [data de consulta: maig 2022]. Disponible a:
[https://ca.wikipedia.org/wiki/Realitat_augmentada](https://ca.wikipedia.org/wiki/Realitat_augmentada)

* VV.AA. ***Google Maps*** [en línia]. Viquipèdia, 25 d’agost de 2021. [data de consulta: maig 2022]. Disponible a:
[https://ca.wikipedia.org/wiki/Google_Maps](https://ca.wikipedia.org/wiki/Google_Maps)

* ***Augmented Reality*** [en línia]. Google AR & VR. [data de consulta: maig 2022]. Disponible a:
[https://arvr.google.com/ar/](https://arvr.google.com/ar/)

* Tilman Reinhardt‎. ***Using Global Localization to Improve Navigation*** [en línia]. Google AI Blog, 11 de febrer de 2019. [data de consulta: maig 2022]. Disponible a:
[https://ai.googleblog.com/2019/02/using-global-localization-to-improve.html?m=1](https://ai.googleblog.com/2019/02/using-global-localization-to-improve.html?m=1)

* Raúl Álvarez. ***La nueva interfaz de Google Maps con realidad aumentada que va a cambiar la aplicación radicalmente*** [en línia]. Xataka, 12 de febrer de 2019. [data de consulta: maig 2022]. Disponible a:
[https://www.xataka.com/aplicaciones/asi-como-navegacion-realidad-aumentada-hace-que-google-maps-sea-util](https://www.xataka.com/aplicaciones/asi-como-navegacion-realidad-aumentada-hace-que-google-maps-sea-util)

* Manovich, Lev. (2013). **El Software toma el mando**. Barcelona: Editorial UOC. 


----

Licencia: Material Creative Commons desarrollado bajo licencia CC BY-SA 4.0. Imágenes CC BY [Tubik studio](https://blog.tubikstudio.com/how-to-create-original-flat-illustrations-designers-tips/) 
