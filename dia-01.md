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

> [!NOTE]
> Com és que hem de fer servir `SHIFT` + `CTRL` + `C` per enganxar text i no
> simplement `CTRL` + `C` com a tot arreu? Perquè `CTRL` + `C` és una
> combinació de tecles especial que serveix per interrompre un programa.

* Enganxar text: `SHIFT` + `CTRL` + `V`
* Moure's a la següent pestanya: `CTRL` + `PgDown`
* Moure's a l'anterior pestanya: `CTRL` + `PgUp`
* Fer el text més gran: `CTRL` + `+`
* Fer el text més petit: `CTRL` + `-`

Obrint la configuració podem configurar moltes coses, com ara la mida i el
tipus de lletra, els colors, etc.

### L'arbre de directoris

Hem dit que el símbol `~` es refereix al nostre directory personal o `HOME`.
Anem a veure com funciona l'arbre de directoris. S'anomena arbre perquè una
carpeta en pot contenir d'altres, de la mateixa manera que d'una branca en
poden sortir d'altres.

Quan iniciem el terminal per primera vegada, ens situarà per defecte dins del
directori `HOME`. Vols saber quins fitxers i carpetes conté el directory
`HOME`? Hauràs d'executar una comanda per saber-ho:

```
$ ls
```

En el quadre anterior, faig servir el símbol `$` per indicar que has d'executar
una comanda a la línia d'ordres. En aquest cas, la comanda és `ls`. Quan ho
facis i després d'apretar `Enter`, veuràs un resultat com el següent:

```
$ ls
Downloads
Desktop
un-fitxer-qualsevol.txt
```

Normalment els text dels directoris és d'un color com ara blau i els arxius
normals de color blanc.

Com ho podem per veure els fitxers que estan dins del directori `Desktop`?

```
$ ls Desktop/
Fotos_colònies_2023
el-meu-fitxer-1.txt
el-meu-fitxer-2.txt
```

El text que posem després de la comanda `ls` l'anomenem "paràmetre" i el fem
servir per modificar el comportament de la comanda o per passar-li informació
adicional. En aquest cas, el paràmetre és el nom del directori i serveix per
indicar a `ls` que ens mostri el contingut del directori `Desktop`

El caràcter `/` al final del nom del directory no cal posar-lo, però si fem
servir l'auto-completat per no haver descriure tant, ens el posarà
automàticament.

Auto-comple-què? L'auto-completat, és una de les funcionalitats més útils del
terminal, juntament amb la història. Fes la prova, escriu `ls Desk` i apreta la
tecla `Tab`. Si el directori `Desktop` existeix, veuràs que el text que falta
s'escriurà sol.

Ja que ho anomenes, la història què és? Descobreix-ho tu mateix: apreta `CTRL`
+ `P` (`P` de previ) i veuràs que hi haurà la comanda que has executat
anteriorment al prompt, a punt per tornar-se a executar. Per mostrar la
comanda següent has d'apretar `CTRL` + `N` (`N` de next).

Tornem al caràcter `/` que ens ha posat l'auto-completat després del directori,
s'anomena "separador de camí" (path separator). Serveix per separar diferents
parts del "camí" que recorrem fins arribar a un directori o fitxer. Per
exemple:

```
$ ls ~/Desktop/Fotos_colònies_2023/piscina1.jpeg
```

A partir del directori `~` travessem `Desktop`, `fotos_colònies_2023` i
finalment el fitxer `piscina1.jpeg`.

Ara, introduim un altre concepte: el directori de treball. Ja hem dit que quan
obrim el terminal, el directori de treball serà el `HOME`. Si volem saber quin
és el directori de treball fem servir la comanda `pwd` (print working
directori)

```
$ pwd
/home/albert
```

Vaja, `pwd` ens ha mostrat `/home/albert` i no `~` com havíem dit? Això és
perquè `~` en realitat és un "alies", un sinònim de `/home/albert`.

En realitat, l'arbre de directoris no comença al nostre directori personal,
sino a l'arrel de l'arbre, a la qual ens podem referir com a `/`.

A partir d'aquí, podem començar a pujar per l'arbre. El primer directori que
trobem abans d'arribar al nostre personal és un directori anomenat `home` i
dins de `home` i han tots els directoris personals dels usuaris, com ara
`albert`.

Un parell de conceptes nous més: "camí (path) absolut" i "camí relatiu". Tenim
un camí absolut quan el nostre camí comença per `/`. Sigui quin sigui el nostre
directory de treball, si utilitzem un camí absolut, arribarem on volem arribar.
Per exemple, suposem que el nostre directori de treball és `~/Desktop`:

```
$ pwd
/home/albert/Desktop
```

Si volem llistar el contingut del directory `Downloads` situat a
`/home/albert`, hem de fer servir un camí absolut i escriure:

```
$ ls /home/albert/Downloads
```

Per contra, tenim un camí relatiu quan el nostre camí no comença per `/`. Per
exemple, suposem que estem a `~`, podem llistar el continugt de `Desktop` fent
servir un camí relatiu:

```
$ pwd
/home/albert
$ ls Desktop
```

En canvi, si el nostre directori de treball és `/home/albert/Desktop` i fem
servir un camí relatiu per llistaar el contingut de `Downloads`, obtindrem un
error perquè el directori no existeix:

```
$ pwd
/home/albert/Desktop
$ ls Downloads
ls: Downloads: No such file or directory
```

> [!NOTE]
> Pot ser que el missatge d'error ens surti en català depenent com tinguem
> configurada la llengua del sistema.

Anem acabant: a cada directori hi han dos directoris especials: `.` i `..`. `.`
fa referència al directori mateix i `..` al directori pare.

Per exemple, imaginem que el nostre directori de treball és `/home/albert/Desktop` i volem llistar el contingut del directori `~`. Podem fer servir un camí absolut:

```
$ pwd
/home/albert/Desktop
$ ls /home/albert
```

O bé podem fer servir un camí relatiu fent servir `..`:

```
$ pwd
/home/albert/Desktop
$ ls .. 
```

O si volem llistar el contingut de `Downloads`:

```
$ pwd
/home/albert/Desktop
$ ls ../Downloads 
```

### Algunes comandes per començar a fer servir la línia d'ordres

### L'editor de text
