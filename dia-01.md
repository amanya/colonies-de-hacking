# Colònies de Hacking

## Dia 1 -- Coneixem l'entorn

Avui et donaré algunes indicacions per poder seguir fàcilment la resta de dies
de les colònies. Segurament hi haurà força coses que no acabes d'entendre. No
et preocupis, les coses més importants les anirem veient durant el curs.
Procuraré anar posant enllaços a llocs on podràs ampliar la informació.

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
et recomano que la investiguis pel teu compte!

Com que Linux és un sistema operatiu lliure i format de moltes peces diferents,
han aparegut diferentes maneres d'instal·lar-lo, i configurar-lo anomenades
*distribucions*. Segurament la distribució més popular és
[Ubuntu](https://ubuntu.com/) i és la que teniu instal·lada al vostre
ordinador.

[^1]: GNU és l'[acrònim
    recursiu](https://ca.wikipedia.org/wiki/Acr%C3%B2nim_recursiu) de GNU is
    Not Unix, aparentment fa molta gràcia als hackers 🤷.

[^2]: Carpeta.

### L'entorn d'escriptori

L'[entorn d'escriptori](https://ca.wikipedia.org/wiki/Entorn_d%27escriptori) és
el conjunt de programes que ofereixen una interfície gràfica a l'usuari d'un
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

En aquest curs no entrarem en gaires detalls de com fer-lo servir però si que
necessitarem fer una cosa: executar programes, concretament el navegador web i
el terminal.

Per fer-ho, un cop hagis fet *login* fent servir la teva compta d'usuari
(nom i contrassenya), veuràs l'escriptori de Gnome. En aquest moment simplement
has d'apretar la tecla Windows (la que té uns quadradets). En Linux aquesta
tecla s'anomena `Super`.

Quan ho fas, ens mostra totes les aplicacions que tens obertes i també fa
aparèixer un quadre de text. En aquest moment pots començar a escriure el nom
de l'aplicació que vols obrir, per exemple "firefox". Només cal que escriguis
les primeres lletres i veuràs que ja apareix com a primer resultat. Apreta
`Enter` i s'obrirà.

Per obrir el terminal fes el mateix però escriu "terminal".

### El terminal

L'emulador de terminal,
[terminal](https://ca.wikipedia.org/wiki/Terminal_d%27ordinador) o simplement
"pantalla negra" és una eina per comunicar-te amb el sistema operatiu fent
servir el teclat i comandes de text (al contrari que si fas servir el ratolí
per comunicar-te fent servir l'entorn d'escriptori).

El terminal que faràs servir és el Gnome Terminal, que forma part de l'entorn
d'escriptori Gnome. Evidentment, n'hi ha molts d'altres. També hi ha terminals
en Windows i MacOS.

Quan inicies el terminal, el primer que fa és executar un intèrpret d'ordres,
un programa capaç d'entendre certes comandes que li escrius a l'indicador
(prompt en anglès). En el teu cas, el prompt només conté una fletxa (➜), el
símbol `~` i el cursor (un quadradet que es mou per indicar on escriuràs el
següent caràcter.

El símbol `~` és un sinònim per al directori `HOME`, la carpeta a partir de la
qual desaràs els teus arxius personals.

El terminal té diverses funcions interessants:

* Obrir una nova pestanya (igual que un navegador web): `SHIFT` + `CTRL` + `T`
* Tancar una pestanya: `SHIFT` + `CTRL` + `W`
* Copiar text: `SHIFT` + `CTRL` + `C`

> [!NOTE]
> Per què hem de fer servir `SHIFT` + `CTRL` + `C` per enganxar text i no
> simplement `CTRL` + `C` com a tot arreu? Perquè `CTRL` + `C` és una
> combinació de tecles especial que serveix per interrompre un programa.

* Enganxar text: `SHIFT` + `CTRL` + `V`
* Moure's a la següent pestanya: `CTRL` + `PgDown`
* Moure's a l'anterior pestanya: `CTRL` + `PgUp`
* Fer el text més gran: `CTRL` + `+`
* Fer el text més petit: `CTRL` + `-`

Obrint la configuració pots configurar moltes coses, com ara la mida i el
tipus de lletra, els colors, etc.

### L'arbre de directoris

Hem vist que el símbol `~` es refereix al nostre directori personal o `HOME`.
Vejem com funciona l'arbre de directoris. S'anomena arbre perquè una carpeta en
pot contenir d'altres, de la mateixa manera que de la branca d'un arbre en
poden sortir d'altres.

Quan iniciem el terminal per primera vegada, ens situarà per defecte dins del
directori `HOME`. Vols saber quins fitxers i carpetes conté el directori
`HOME`? Hauràs d'executar una comanda per saber-ho:

```
$ ls
```

En el quadre anterior, faig servir el símbol `$` per indicar que has d'executar
una comanda a la línia d'ordres. Quan ho facis, copia només la comanda, no el
símbol `$`. En aquest cas, la comanda és `ls`. Quan ho facis i després
d'apretar `Enter`, veuràs un resultat semblant al següent:

```
$ ls
Downloads
Desktop
un-fitxer-qualsevol.txt
```

Normalment el text dels directoris és d'un color com ara blau i el dels arxius
normals de color blanc.

Com ho podem fer per veure els fitxers que estan dins del directori `Desktop`?

```
$ ls Desktop/
Fotos_colònies_2023
el-meu-fitxer-1.txt
el-meu-fitxer-2.txt
```

El text que posem després de la comanda `ls` s'anomena "paràmetre" i serveix
per modificar el comportament de la comanda o per passar-li informació
adicional. En aquest cas, el paràmetre és el nom del directori i serveix per
indicar a `ls` que ens mostri el contingut del directori `Desktop`.

El caràcter `/` al final del nom del directori no cal posar-lo, però si fas
servir l'auto-completat per no haver descriure tant, te'l posarà
automàticament.

*Auto-comple-què*? L'auto-completat, és una de les funcionalitats més útils del
terminal, juntament amb la història. Fes la prova, escriu `ls Desk` i apreta la
tecla `Tab`. Si el directori `Desktop` existeix, veuràs que el text que falta
s'escriurà sol.

Ja que ho anomenes, la història què és? Descobreix-ho tu mateix: apreta `CTRL`
+ `P` (`P` de previ) i veuràs que hi haurà la comanda que has executat
anteriorment al prompt, a punt per tornar-se a executar. Per mostrar la
comanda següent has d'apretar `CTRL` + `N` (`N` de next). També pots fer servir
les fletxes amunt o avall per anar a la comanda anterior o a la següent, però
fer-ho amb `CTRL` + `P` o `CTRL` + `N` té dos avantatges molt interessants: 1.
no has de desplaçar la mà cap a on hi ha les fletxes, de manera que estàs a
punt per seguir escribint comandes a tort i a dret i 2. és més hacker fer-ho
així ;) 

Tornem al caràcter `/` que ens ha posat l'auto-completat després del directori,
s'anomena "separador de camí" (path separator). Serveix per separar diferents
parts del "camí" que recorrem fins arribar a un directori o fitxer. Per
exemple:

```
$ ls ~/Desktop/Fotos_colònies_2023/piscina1.jpeg
```

A partir del directori `~` travessem `Desktop`, `fotos_colònies_2023` i
finalment el fitxer `piscina1.jpeg`.

Ara, introdueixo un altre concepte: el directori de treball. Ja he dit que quan
obres el terminal, el directori de treball serà el `HOME`. Si vols saber quin
és el directori de treball fes servir la comanda `pwd` (print working
directori):

```
$ pwd
/home/albert
```

Vaja, `pwd` t'ha mostrat `/home/albert` i no `~`? Això és perquè `~` en
realitat és un "alies", un sinònim de `/home/albert`. Si et diguèssis Maria,
potser el teu directori personal seria `/home/maria` i per tant `~` seria
equivalent a `/home/maria`.

En realitat, l'arbre de directoris no comença al teu directori personal, sino a
l'arrel de l'arbre, a la qual et pots referir com a `/`.

A partir d'aquí, pots començar a pujar per l'arbre. El primer directori que
trobes abans d'arribar al teu personal és un directori anomenat `home` i
dins de `home` i han tots els directoris personals dels usuaris, com ara
`albert`.

Un parell de conceptes nous més: "camí (path) absolut" i "camí relatiu". Un
camí absolut és quan el camí comença per `/`. Sigui quin sigui el
directori de treball, si utilitzes un camí absolut, arribaràs on vols arribar.
Per exemple, suposa que el teu directori de treball és `~/Desktop`:

```
$ pwd
/home/albert/Desktop
```

Si vols llistar el contingut del directori `Downloads` situat a
`/home/albert`, has de fer servir un camí absolut i escriure:

```
$ ls /home/albert/Downloads
```

Per contra, un camí és relatiu quan el camí no comença per `/`. Per exemple,
suposem que estem a `~`, podem llistar el contingut de `Desktop` fent servir un
camí relatiu:

```
$ pwd
/home/albert
$ ls Desktop
```

D'altra banda, si el teu directori de treball és `/home/albert/Desktop` i fas
servir un camí relatiu per llistar el contingut de `Downloads`, obtindras un
error perquè el directori no existeix:

```
$ pwd
/home/albert/Desktop
$ ls Downloads
ls: Downloads: No such file or directory
```

> [!NOTE]
> Pot ser que el missatge d'error et surti en català depenent com tinguis
> configurada la llengua del sistema.

Anem acabant: a cada directori hi han dos directoris especials: `.` i `..`. `.`
fa referència al directori mateix i `..` al directori pare.

Per exemple, imagina que el teu directori de treball és `/home/albert/Desktop`
i vols llistar el contingut del directori `~`. Pots fer servir un camí absolut:

```
$ pwd
/home/albert/Desktop
$ ls /home/albert
```

O bé pots fer servir un camí relatiu fent servir `..`:

```
$ pwd
/home/albert/Desktop
$ ls .. 
```

O si vols llistar el contingut de `Downloads`:

```
$ pwd
/home/albert/Desktop
$ ls ../Downloads 
```

### Algunes comandes per començar a fer servir la línia d'ordres

#### `cd`: Canvia el directori de treball

* Ves a `HOME`:
```
$ cd ~
$ pwd
/home/albert
```

* Canvi de directori fent servir un camí relatiu:
```
$ cd Desktop
```

* Canvi de directori fent servir un camí absolut:
```
$ cd /home
```

#### `mkdir`: Crea un directori

```
$ mkdir el-meu-dir
$ ls
el-meu-dir
$ cd el-meu-dir
```

#### `rmdir`: Esborra un directori

```
$ rmdir el-meu-dir
```

> [!NOTE]
> El directori que vols esborrar ha d'estar buit (no pot contenir cap fitxer o
> carpeta).

### L'editor de text

L'editor de text és un dels programes que fa servir més un hacker. Serveix per
escriure els programes d'una manera ràpida i eficient però també el pots fer
servir per escriure qualsevol cosa: des de les instruccions de com fer servir
el darrer programa que has escrit (això s'anomena documentació) fins al teu
diari personal.

Els editors de text que fan servir els hackers, tenen una característica
important: només poden treballar amb [text
pla](https://ca.wikipedia.org/wiki/Text_pla). Anomenem text pla al text format
només per caràcters sense format. Això vol dir que en un arxiu de text pla, no
hi podem indicar coses com el color del text ni la mida ni tampoc hi podem
posar taules o imatges.

Però no et preocupis perquè a poc a poc aniràs descobrint que treballar amb
fitxers de text pla te moltes avantatges i a més a més, veuràs com l'editor de
text pot entendre el codi que escrius i posar-li automàticament colors per
fer-lo més fàcil de llegir. I també t'ensenyaré com pots crear documents amb
format (títols, subtítols, negreta, taules, etc) com aquest que estàs llegint
fent servir només text pla.

L'editor de text que faràs servir durant les colònies s'anomena
[Neovim](https://neovim.io/). Neovim és un editor que està basat en un editor
anterior anomenat [Vim](https://www.vim.org/). Vim vol dir "vi improved". Què
vol dir [vi](https://ca.wikipedia.org/wiki/Vi_(UNIX))? Doncs és un altre editor
anterior que es va crear l'any 1976 que al mateix temps estava basat en altres
editor més antics. Ja veus que aquí s'aprofita tot.

> [!NOTE]
> Potser hi haurà gent que si veu que t'ensenyo a fer servir un editor com *Vi*
> alertarà serveis socials per sospites de maltractament a menors, però jo no
> hi estic d'acord; per diverses raons. És veritat que Vi no és un editor fàcil
> de fer servir ni de configurar, però tan sols necessites aprendre quatre
> coses bàsiques per començar a treure-li el suc.
>
> Les comandes bàsiques de Vi son tan útils que tots els editors considerats
> més moderns ofereixen un "mode Vi" on les podràs fer servir. Per tant aquest
> coneixement et servirà sempre.
>
> Una altra cosa que m'agrada de Vim i Neovim és que son editors programables.
> Els dos incorporen un llenguatge de programació integrat garantitzant hores i
> hores de diversió sense límits.

La caracteristica més important dels editors tipus `Vi` és que son "modals".
Modal vol dir que té diversos modes de funcionament: normal, inserció, comandes
o visual.

Petit resum dels modes de Vi:

* **Normal**: És el mode que trobes quan llançem Vi. És el mode on et passes
  més estona doncs et permet navegar pel text, copiar/retallar/enganxar
  caracters, paraules o línies, fer i desfer i molt més. Apreta `Esc` per
  tornar al mode normal des de qualsevol altre mode.

* **Inserció**: És el mode que ens permet escriure el text, com fariem en
  qualsevol altre editor. Hi han tres maneres d'accedir-hi:
  * `i` (insert): accedeix directament al mode d'inserció
  * `a` (afegir): accedeix al mode d'inserció i mou el cursor al següent
    caracter
  * `o` (obrir): accedeix al mode d'inserció i afegeix una línia nova sota on
    és el cursor

* **Comandes**: És una manera d'executar comandes més complexes que les que
  podem fer al mode Normal. Per accedir-hi apreta `:` des del mode Normal

* **Visual**: Serveix per seleccionar àrees de text i transformar-lo de
  diverses maneres.
