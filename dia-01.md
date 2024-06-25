# Colònies de Hacking

## Dia 1 -- Coneixem l'entorn

Avui us donaré quatre indicacions per poder seguir fàcilment la resta de dies
de les colònies. Segurament hi haurà força coses que no acabeu d'entendre. No
us preocupeu doncs les coses més importants les anirem veient durant el curs.
Procuraré anar posant enllaços a llocs on podreu ampliar la informació.

### El sistema operatiu

El sistema operatiu és el primer programa que s'executa quan s'engega un
ordinador, mòbil, tauleta, etc. El sistema operatiu sap com parlar amb el
*maquinari* (pantalla, teclat, memòria, etc) i t'ofereix una interfície per a
que tu t'hi puguis comunicar. Per exemple, el sistema operatiu dibuixa les
finestres, els botons, els quadres de text. Però també sap com llegir el
moviment del ratolí o com desar fitxers al disc. També sap rebre i enviar dades
a través d'una xarxa com ara internet.

La majoria d'ordinadors tenen un sistema operatiu de l'empresa Microsoft
instal·lat anomenat *Windows*. Els ordinador Apple, fan servir un sistema
operatiu anomenat MacOS. El sistema operatiu dels iPhones es diu iOS.

Tots aquests sistemes operatius són propietat de les seves respectives empreses
i només ells decideixen com funciona, quines funcionalitats implementen, etc.

Nosaltres, farem servir un sistema operatiu de [programari
lliure](https://ca.wikipedia.org/wiki/Programari_lliure) anomenat GNU/Linux o
simplement Linux per fer-ho més curt. No és propietat de cap empresa sinó que
molts programadors i empreses de tot el mon col·laboren per desenvolupar-lo.

GNU[^1] fa referència al conjunt d'eines bàsiques que formen el sistema
operatiu, com ara els programes per mostrar quins arxius hi ha en un
directori[^2]. [Linux](https://ca.wikipedia.org/wiki/Linux) és l'anomenat
*nucli* del sistema operatiu. És el programa que s'encarrega d'entendre com
funciona el *maquinari* de l'ordinador. La seva història és molt interessant,
us recomano que la investigueu pel vostre compte!

Com que Linux és un sistema operatiu lliure i format de moltes peces diferents,
han aparegut diferentes maneres d'instal·lar-lo, anomenades *distribucions*.
Segurament la distribució més popular és [Ubuntu](https://ubuntu.com/) i és la
que teniu instal·lada al vostre ordinador.

[^1]: GNU és l'[acrònim
    recursiu](https://ca.wikipedia.org/wiki/Acr%C3%B2nim_recursiu) de GNU is
    Not Unix, aparentment fa molta gràcia als hackers 🤷.

[^2]: Carpeta.

### L'entorn d'escriptori

L'[entorn d'escriptori](https://ca.wikipedia.org/wiki/Entorn_d%27escriptori) és
el conjunt de programes que ofereixen una iterfície gràfica a l'usuari d'un
ordinador, en resum: dibuixa les finestres, els botons, les caixes de text,
etc, i li dona un aspecte homogeni permetent personalitzar-lo. Per exemple, si
posem el mode fosc, totes les finestres passen a dibuixar-se utilitzant els
colors del mode fosc. Això és responsabilitat de l'entorn d'escriptori.

Una conseqüència del codi lliure, és que sovint hi han diferents maneres de
solucionar un problema. Ja hem vist que hi ha diferents distribucions, però
també hi ha diferents editors de text, programes de dibuix, etc. També tenim
més d'un entorn d'escriptori.

L'entorn d'escriptori que ve per defecte amb Ubuntu es diu
[Gnome](https://www.gnome.org/).

En aquest curs no entrarem en gaires detalls de com funciona però si que
necessitarem fer una cosa: executar programes, concreatament el navegador web i
el terminal.

Per fer-ho, un cop haguem fet *login* fent servir la nostra compta d'usuari
(nom i contrassenya), veurem l'escriptori de Gnome. En aquest moment simplement
hem d'apretar la tecla Windows (la que té uns quadradets). En Linux aquesta
tecla s'anomena `Super`.

Quan ho fem, ens mostra totes les aplicacions que tenim obertes i també fa
aparèixer un quadre de text. En aquest moment podem començar a escriure el nom
de l'aplicació que volem obrir, per exemple "firefox". Només cal que escriguem
les primeres lletres i veurem que ja ens apareix com a primer resultat. Apretem
`Enter` i s'obrirà.

Per obrir el terminal fem el mateix però escribim "terminal".

### El terminal

L'emulador de terminal,
[terminal](https://ca.wikipedia.org/wiki/Terminal_d%27ordinador) o simplement
"pantalla negra" és una eina per comunicar-nos amb el sistema operatiu fent
servir el teclat i comandes de text (al contrari que si fem servir el ratolí
per comunicar-nos fent servir l'entorn d'escriptori).

El terminal que farem servir és el Gnome Terminal, que forma part de l'entorn
d'escriptori Gnome. Evidentment, n'hi ha molts d'altres. També podem trobar
terminals en Windows i MacOS.

Quan iniciem el terminal, el primer que fa és executar un intèrpret d'ordres,
un programa capaç d'entendre certes comandes que li escribim a l'indicador
(prompt en anglès). En el nostre cas, el prompt només conté una fletxa (➜), el
símbol `~` i el cursor (un quadradet que es mou per indicar on escriurem el
següent caràcter.

El símbol `~` és un sinònim per al directori `HOME`, la carpeta a partir de la
qual desarem els nostres arxius personals.

El terminal té diverses funcions interessants:

* Obrir una nova pestanya (igual que un navegador web): `SHIFT` + `CTRL` + `T`
* Tancar una pestanya: `SHIFT` + `CTRL` + `W`
* Copiar text: `SHIFT` + `CTRL` + `C`

> [!NOTE] Com és que hem de fer servir `SHIFT` + `CTRL` + `C` per enganxar text
> i no simplement `CTRL` + `C` com a tot arreu? Perquè `CTRL` + `C` és una
> combinació de tecles especial que serveix per interrompre un programa.

* Enganxar text: `SHIFT` + `CTRL` + `V`
* Moure's a la següent pestanya: `CTRL` + `PgDown`
* Moure's a l'anterior pestanya: `CTRL` + `PgUp`
* Fer el text més gran: `CTRL` + `+`
* Fer el text més petit: `CTRL` + `-`

Obrint la configuració podem configurar moltes coses, com ara la mida i el
tipus de lletra, els colors, etc.

### L'arbre de directoris

### Algunes comandes per començar a fer servir la línia d'ordres

### L'editor de text
