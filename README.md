# FormulariosXMLandXSL

## Información del proyecto

Continuación de la práctica Formularios XML en la cual se cambiarán los modos de acceso al XML mediante XPath, y se añadirá una tabla con la información del XML mediante un archivo XSL formateada.

------------------------------------------

## Modificaciones a realizar:

- Modifica l'accés a l'objecte xmlDoc (corresponent al document xml llegit) per obtenir les opcions de tipus select, select multiple, checkbox i radio. L'accés s'ha de fer mitjançant Xpath. Modifica les funcions posarDadesHtml per llegir els nodes que surten de la cerca amb Xpath. (Nivell: fàcil) (fins a 3 punts)

- Crea questions.xsl i modifica el fitxer (o fes una còpia) questions.xml per posar l'enllaç a questions.xsl de tal forma que si obris directament el fitxer questions.xml el navegador fa una transformació simple per presentar les preguntes, totes les opcions i les respostes a una taula. (Nivell: fàcil) (fins a 3 punts)

-  Inclou codi per forçar a l'usuari a respondre totes les preguntes. (Veure aplicació d'exemple) (Nivell: mitjà) (fins a 2 punts)

- Modifica el codi per que l'aplicació faci la correcció personalitzada modificant l'objecte xmlDoc i mostrant-ho amb una XSLT al client. Js farà només el càlcul de la nota final i ho mostrará després dels resultats. (Nivell: difícil) (fins a 2 punts)

- Aprofita per millorar la presentació, especialment per donar estil a la taula resultant de la XSLT. (fins a 2 punts)