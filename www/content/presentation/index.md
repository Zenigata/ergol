+++
title = "Présentation"

[params]
cssSheets = ["/css/keebs.css"]
jsModules = ["/js/x-keyboard.js"]
jsScripts = ["/js/keebs.js"]
footer = "propulsé par [x-keyboard](https://onedeadkey.github.io/x-keyboard)"
+++

{{<x-keyboard name="Ergo‑L" data="ergol" class="odk" href="/installation">}}

:::{.highlight}
- [Ergonomique avant tout !]
  <br> – Réduit les extensions de doigt, les déviations ulnaires, l’effort de saisie.
  <br> – Compatible avec **tous** les claviers ergonomiques, de 33 à 105 touches.
  <br> – Préserve les raccourcis clavier et les chiffres en direct.
- [Plus optimisé que Dvorak et Bépo]
  <br> Deux fois moins de SFU que Bépo en français **et** que Dvorak en anglais.
- [Impeccable en français]
  <br> Une seule touche morte pour produire tous les caractères spéciaux.
- [Efficace en anglais]
  <br> La première disposition francophone **réellement** optimisée pour l’anglais.
- [Redoutable pour le code]
  <br> Une couche de symboles optionnelle et optimisée pour le code est
  disponible en [AltGr]{.kbd}.
:::


Ergonomique avant tout !
--------------------------------------------------------------------------------

### 1DFH, « <i lang="en">1u distance from home</i> »

Ergo-L intègre l’approche 1DFH, qui consiste à ne pas déplacer ses doigts de
plus d’une touche (« 1u », pour « une unité », désignant la distance entre deux
touches) par rapport à la position de repos. Cela permet un gain de
confort important pour la saisie en méthode dactylo, en évitant notamment les
extensions latérales de l’auriculaire droit, qui sont typiques de Bépo pour les
lettres `m` `z` `w` `ç`.

![Ergo‑L sur un clavier compact (type OLKB Planck).](ergol_1dfh.svg)

C’est pour suivre cette approche que l’immense majorité des claviers
ergonomiques actuels ne propose que six colonnes de touches par main, ce qui est :

- compliqué avec AZERTY, qui a les touches [Ù]{.kbd} et <kbd>^</kbd> en
6<sup>e</sup> colonne et oblige à déplacer [Entrée]{.kbd} et [Backspace]{.kbd} ;
- **très** compliqué avec Bépo, qui, outre [M]{.kbd} et [Z]{.kbd} en
6<sup>e</sup> colonne, a [W]{.kbd} et [Ç]{.kbd} en 7<sup>e</sup> colonne à
déplacer également ;
- trivial avec Ergo‑L, qui a été conçu pour ça.

Les [claviers ergonomiques](/claviers) modernes cherchent à limiter le nombre total de
touches, en utilisant différents *layers* pour amener les touches excentrées
sous les doigts, plutôt que l’inverse. Nous avons donc décidé de n’utiliser
aucune touche en dehors du pavé de 3×10 touches centrales pour les lettres et
les symboles de programmation. Ergo‑L est ainsi compatible avec les claviers les
plus compacts (33 touches au minimum) sans ajustement majeur.


### Adapté à la bureautique

Les raccourcis claviers usuels
[Ctrl]{.kbd}‑[Q]{.kbd}[A]{.kbd}[S]{.kbd}[Z]{.kbd}[X]{.kbd}[C]{.kbd}[V]{.kbd}
sont devenus indispensables pour une utilisation avec la souris en main droite.
Les approches de type [Dvorak][], très antérieures à la généralisation de la
bureautique (le Dvorak a été finalisé en 1932), ignorent ces raccourcis clavier
en plaçant toutes les voyelles sous la main gauche ; mais les approches modernes
comme Colemak et Workman permettent de conserver ces raccourcis tout en obtenant
de meilleures métriques.

Ergo‑L suit cette approche [Colemak][]/[Workman][] et, comme eux, s’autorise un
changement : le [C]{.kbd} est ainsi déplacé pour favoriser les enchainements,
mais [Ctrl]{.kbd}‑[C]{.kbd} reste faisable d’une main à gauche.


### Réduction de la fatigue de saisie

Ergo‑L veille à réduire autant que possible :

- **les déviations ulnaires**, en proposant une alternative en [AltGr]{.kbd} à
  tous les symboles placés sur des touches excentrées ;
- **la charge des doigts faibles**, surtout celle de l’auriculaire droit,
  responsable de [Entrée]{.kbd} et [Backspace]{.kbd} sur la plupart des
  claviers ;
- **le taux de bigrammes de même doigt**, un type d’enchainement très
  inconfortable, notamment à haute vitesse de saisie.

Ergo‑L privilégie le confort à la vitesse : on peut taper vite avec n’importe
quel clavier. Mais il est conçu pour que son confort et son ergonomie ne se
dégradent pas au fur et à mesure que la vitesse de saisie augmente.


Plus optimisé que Dvorak et Bépo
--------------------------------------------------------------------------------

[Dvorak][] est la disposition de clavier optimisée la plus connue. Elle fut
développée pendant l’entre-deux-guerres pour les machines à écrire, qui ont
d’importantes contraintes physiques dont les claviers modernes sont exemptés :
typiquement, appuyer sur deux touches côte à côte est un excellent moyen de
coincer les marteaux. Cela implique qu’il fallait privilégier les alternances de
mains aux <abbr title="Enchainements de deux touches actionnées par deux doigts
différents d’une même main, comme 'df' en AZERTY">roulements</abbr>, alors que
ces derniers sont très confortables sur un clavier d’ordinateur.

Dvorak était un grand pas en avant, mais se base sur une philosophie qui
n’est plus pertinente aujourd’hui. Malheureusement, [Bépo][] et ses nombreuses
variantes la reprennent sans chercher à la mettre à jour.

Dvorak et Bépo ne sont optimisés que pour une seule langue (anglais et français,
respectivement) et sont très inconfortables dans l’autre. Pourtant, à une
exception près, les neuf lettres les plus fréquentes sont les mêmes en français
(`esanitruo`) et en anglais (`etaohnisr`) :

:::{ style="overflow: scroll;" }
|      |      E |      S |      A |      N |      I |      T |      R |      U |      O |      H |
|    -:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|**fr**| 14,4 % |  7,2 % |  7,1 % |  6,8 % |  6,7 % |  6,7 % |  6,5 % |  6,1 % |  5,3 % |  1,0 % |
|**en**| 11,7 % |  6,1 % |  8,0 % |  6,6 % |  6,5 % |  9,0 % |  5,3 % |  2,7 % |  7,8 % |  6,7 % |
: Fréquence des lettres les plus utilisées en français et en anglais.
:::

Ergo‑L place donc ces lettres aux emplacements les plus confortables (au sens de
[Workman][]) et fait en sorte qu’aucun enchainement fréquent en français ou en
anglais ne soit rédhibitoire. Comme en [Colemak][], on cherche à limiter le plus
possible le taux de bigrammes de même doigt, en favorisant les roulements au
même titre que les alternances de mains.

Bien qu’il soit **optimisé pour les deux langues, français _et_
anglais**, Ergo‑L affiche de meilleures métriques d’optimisation, tant sur la
charge des doigts que sur le taux de bigrammes de même doigt :

<style>
.sfu table tr td:nth-child(4) { background-color: var(--bg-accent); }
.sfu table caption { margin-top: 0.5em; font-size: smaller; }
.sfu table { margin: 1em auto; max-width: 50em; border-collapse: collapse; }
</style>

:::{.sfu style="overflow: scroll;" }
|      |  AZERTY                       |  Bépo                       |  Ergo‑L                       |  Dvorak                       |  QWERTY                       |
|    -:|:-----------------------------:|:---------------------------:|:-----------------------------:|:-----------------------------:|:-----------------------------:|
|**fr**| [7,97 %](/stats/#/azerty//fr) | [2,55 %](/stats/#/bepo//fr) | [1,22 %](/stats/#/ergol//fr) | [3,31 %](/stats/#/dvorak//fr) | [7,16 %](/stats/#/qwerty//fr) |
|**en**| [6,31 %](/stats/#/azerty//en) | [3,01 %](/stats/#/bepo//en) | [1,20 %](/stats/#/ergol//en) | [2,62 %](/stats/#/dvorak//en) | [5,76 %](/stats/#/qwerty//en) |
: Taux de bigrammes de même doigt en français et anglais, extrait de la [page de comparaison avec Bépo](/bepo).
:::


Impeccable en français
--------------------------------------------------------------------------------

### Caractères accentués

La gestion des accents, diacritiques et symboles typographiques français
nécessite traditionnellement l’usage de touches excentrées (ce qui irait à
l’encontre de l’approche [1DFH][] d’Ergo‑L) ou de [AltGr]{.kbd} (ce qui est
source d’erreur à haute vitesse, car il faut relâcher la touche au bon moment).

Ergo‑L utilise une touche morte [★]{.odk} de type [Lafayette][] pour tous les
caractères accentués, diacritiques et signes de ponctuation spéciaux. Actionner
cette touche Typo donne accès à **tous** ces symboles dans le pavé de
3×10 touches, **sans** utiliser [AltGr]{.kbd}. Cela occasionne [de 2,5 % à
4,0 % de frappes supplémentaires](/bepo/#typographie-ergol) pour un texte
francophone, ce qui nous semble négligeable comparé au gain de confort obtenu.

![La touche morte d’Ergo‑L.](ergol_1dk.svg)

- [★]{.odk} [lettre] = accent grave ou altération (`à` `è` `ù` `ç` `œ`)
- [★]{.odk} [touche à gauche d’une voyelle] = voyelle avec accent aigu (`é`)
- [★]{.odk} [touche à l’intérieur ou au-dessus] = voyelle avec circonflexe
  (`â` `ê` `î` `ô` `û`)
- … et d’autres altérations : `æ` `µ` `ß` `ñ`, etc.

La touche [★]{.odk} donne parfois accès à une autre touche morte :

- [★]{.odk} [★]{.odk} = tréma mort (`ä` `ë` `ï` `ö` `ü` `ÿ`, etc.)
- [★]{.odk} [G]{.kbd} = touche morte pour les lettres grecques (`α` `β` `γ`, etc.)


### Typographie

Soigner la typographie demande souvent un effort (physique et mental) non négligeable.
Beaucoup l’ignorent, ou laissent leur éditeur de texte la gérer pour eux. Ergo‑L permet
de soigner la typographie sans aucun effort supplémentaire :

- [Shift]{.kbd}‑[Espace]{.kbd} = espace insécable fine
- [★]{.odk} [Espace]{.kbd} = apostrophe typographique
- [★]{.odk} [D]{.kbd}[B]{.kbd}[V]{.kbd}[-]{.kbd} = tiret bas, cadratin,
  demi-cadratin, insécable
- [★]{.odk} [majuscule] = majuscule accentuée

Les ponctuations hautes (`:` `;` `?` `!`) sont en [Shift]{.kbd} pour faciliter leur
enchainement avec l’insécable fine : on maintient [Shift]{.kbd}, on presse
[Espace]{.kbd} puis la ponctuation, on relâche [Shift]{.kbd}.


### Optimisation

En français, les huit lettres les plus fréquentes (`esanitru`) sont toutes
réparties sur la position de repos des doigts, et le reste des lettres
fréquentes est réparti sur les autres touches faciles d’accès.

Une grande attention à été portée aux enchainements de lettres.

- Les voyelles s’enchainent fréquemment avec toutes les consonnes importantes,
  donc elles sont soit :
    - placées sur les auriculaires, avec des lettres peu fréquentes autour,
      comme [Q]{.kbd}[A]{.kbd}[Z]{.kbd} et [Y]{.kbd}[U]{.kbd}[K]{.kbd} ;
    - empilées sur des doigts plus forts pour celles qui ne s’enchainent pas
      ensemble, comme [E]{.kbd}[O]{.kbd} et [★]{.odk}[I]{.kbd}.
- Le placement des lettres sur les positions de repos maximise les roulements
  vers l’intérieur et minimise les redirections, qui sont source d’erreur à
  haute vitesse.
- Le reste des lettres fréquentes est placé de sorte à minimiser les
  bigrammes de même doigt (par exemple, [D]{.kbd} et [G]{.kbd} s’enchainent très
  souvent avec [N]{.kbd} ou [R]{.kbd}, mais très peu avec [T]{.kbd}).
- La touche morte est placée sur la main opposée à [E]{.kbd}[A]{.kbd}[C]{.kbd},
  qui sont les lettres le plus souvent diacritées en français.

![[Fréquence d’utilisation des touches en français.](/stats/#/Ergo‑L//fr)](ergol_fr.svg)

Pratiquement aucun enchainement courant en français ne demande trop d’effort.


Efficace en anglais
--------------------------------------------------------------------------------

### Même optimisation qu’en français

Ergo‑L porte la même attention au confort de la saisie de texte en anglais qu’en
français, et doit donc faire quelques compromis pour faire cohabiter les deux
langues. Certaines lettres sont beaucoup plus fréquentes dans une langue que dans
l’autre (comme le [U]{.kbd} et la touche [★]{.odk} en français et le [H]{.kbd} en
anglais) et les enchainements courants peuvent être très différents.

Ergo‑L optimise le plus possible la saisie de texte anglais et français sans
causer de problèmes rédhibitoires dans une de ces deux langues. Par exemple,
l’enchainement `TH` (*le* bigramme le plus fréquent en anglais, avec 3,2 %
d’occurences) est très confortable, mais le [H]{.kbd} occupe une place dont on
peut se dispenser en français. De même, [U]{.kbd} et [★]{.odk} sont très
fréquents en français, mais peu fréquents en anglais, ce qui a été pris en
compte pour leur placement.

![[Fréquence d’utilisation des touches en anglais.](/stats/#/Ergo‑L//en)](ergol_en.svg)

Ergo‑L a donc une ergonomie comparable en français et en anglais. Bien que de
nombreuses dispositions dédiées exclusivement à l’anglais soient plus efficaces
qu’Ergo‑L dans cette langue, Ergo‑L est *la première disposition **réellement**
optimisée pour le français **et** l’anglais*.

<!-- Insérer ici une section expliquant pourquoi le É n’est pas en direct ! -->


### Et les autres langues ?

Ergo‑L est capable de saisir du texte dans toutes les langues de l’Union
européenne (utilisant l’alphabet latin) ainsi que l’esperanto et le romaji,
mais ne cherche pas à optimiser la saisie de texte dans d’autres langues que le
français et l’anglais. Certains caractères sont disponibles en touche
[★]{.odk}, comme `ß` ou `ñ`, et il existe de nombreuses touches mortes en
[Shift]{.kbd}‑[AltGr]{.kbd} : par exemple, `^` étant en
[AltGr]{.kbd}‑[Q]{.kbd}, [Shift]{.kbd}‑[AltGr]{.kbd}‑[Q]{.kbd} produit un
accent circonflexe mort.

Cette approche est suffisante pour la saisie occasionnelle de caractères spéciaux.
Pour des usages plus réguliers, plutôt que de chercher à couvrir tous les cas
possibles, nous avons préféré faire en sorte que la disposition soit simple à
personnaliser.

Le [dépôt GitHub d’Ergo‑L](https://github.com/Nuclear-Squid/ErgoL) contient le
fichier source de la disposition – un fichier TOML facile à lire et modifier –
ainsi que des instructions pour construire une disposition personnalisée ou
évaluer la qualité des enchainements d’une variante. Remplacer les caractères
de la touche morte par ceux dont vous avez besoin devrait être relativement
simple, et le résultat sera bien plus efficace que n’importe quelle disposition
de clavier cherchant à couvrir toutes les langues !

![Un exemple d’adaptation d’Ergo‑L pour l’allemand.](ergol_1dk_de.svg)

Si vous voulez adapter Ergo‑L à une langue étrangère, nous vous recommandons de
concevoir la couche Typo uniquement pour cette langue et d’installer votre
adaptation en même temps qu’Ergo‑L en lui donnant un autre nom (comme
« ergol-de » pour l’allemand, par exemple) et des paramètres linguistiques
adaptés (pour avoir la bonne correction orthographique). Tous les bureaux modernes
proposent un raccourci clavier pour basculer d’une langue à une autre, et vous
pourrez ainsi basculer d’Ergo‑L à votre variante spécifique en un clin d’œil.


Redoutable pour le code
--------------------------------------------------------------------------------

### Héritage QWERTY-US

La grande majorité des touches en dehors du pavé de 3×10 sont identiques à
celles de QWERTY‑US. Les seules exceptions sont :

- les chevrons `<` et `>` sur la touche ISO, entre [Shift]{.kbd} et [Z]{.kbd} ;
- les signes `-` et `/` qui sont échangés, le tiret étant très fréquent en français ;
- les signes `;` et `:` qui sont déplacés en [Shift]{.kbd}‑[,]{.kbd} et
  [Shift]{.kbd}‑[.]{.kbd} respectivement.

Cet héritage implique aussi que les chiffres sont en accès direct (sans
[Shift]{.kbd}), ce qui facilite grandement la saisie de nombres.

QWERTY‑US est réputé pour son efficacité dans la saisie de symboles de
programmation, mais reste perfectible : **tous** les symboles de programmation
nécessitent au moins un auriculaire et une extension, car ils sont tous sous un
auriculaire, ou en [Shift]{.kbd}, ou les deux. Ergo‑L a donc à cœur de proposer
une meilleure solution.


### Couche Symboles

Ergo‑L propose une couche Symboles optionelle accessible par [AltGr]{.kbd} et
optimisée pour le placement et les enchainements de symboles de programmation.

![La couche Symboles d’Ergo‑L.](ergol_altgr.svg)

Cette couche est plutôt simple à mémoriser, car les symboles sont
regroupés par « blocs ». On y retrouve :

- les délimiteurs `()` `{}` `[]` `<>` `^$`
  <small>(note : `^` et `$` marquent le début et la fin de ligne dans les
  expressions régulières)</small> ;
- les délimiteurs de chaines de caractères `'` `` ` `` `"` ;
- les symboles arithmétiques `+` `-` `/` `*` ;
- les ponctuations `!` `;` `:` `?`
  <small>(note : `;` `:` sont à leur emplacement en QWERTY européen)</small> ;
- `$` `%` `&` `*` sont à leur position en [Shift]{.kbd}‑chiffre, mais une
  rangée plus bas.

Comme pour l’emplacement des lettres de la disposition, une grande attention a
été portée au placement des symboles de programmation et aux enchainements
courants. Les symboles peu courants (``~@#%^`|``) sont loin des positions de
repos et la grande majorité des enchainements de symboles de programmation se
fait soit avec une alternance de main (`~/`, `);`, `</>`, `+=`, `['']`, etc.)
soit avec un roulement (`>=`, `/*`, `";`, `()`, `\"`, etc.).

Comme pour la saisie de texte en français ou anglais, la couche Symboles
d’Ergo‑L ne contient pratiquement aucun enchainement inconfortable.


### Compatibilité avec Vim

Pour une utilisation technique, Vim apporte une ergonomie reconnue et de
nombreux éditeurs de code implémentent un mode de navigation Vim. La couche
Symboles d’Ergo‑L lui permet de conserver les principales commandes de
déplacement :

- [AltGr]{.kbd}‑[R]{.kbd}/[T]{.kbd} (les touches correspondant à
  [J]{.kbd}/[K]{.kbd} en QWERTY) donne `+`/`-`, qui est une action très proche
  de `j`/`k` ;
- les sauts verticaux `{}`, `()` et `[]` sont en [AltGr]{.kbd} + main gauche.

Cette couche Symboles a été éprouvée dans des contextes techniques variés sans
qu’on relève de problème particulier. Elle a été reprise dans d’autres projets,
notamment [Lafayette] et [Arsenik].


Licence
--------------------------------------------------------------------------------

[WTFPL][] – Do What The Fuck You Want To Public License. Il existe des licences
mieux réputées, mais on en a choisi une dont on comprend tous les mots.


<!--
 !   ╭───────────────────────────────────────────────────────╮
 !   │               Balises pour les liens :                │
 !   ╰───────────────────────────────────────────────────────╯
-->
[1DFH]:      /presentation#dfh-1u-distance-from-home
[WTFPL]:     http://wtfpl.net
[dvorak]:    https://fr.wikipedia.org/wiki/Disposition_Dvorak
[bépo]:      https://bepo.fr
[workman]:   https://workmanlayout.org
[colemak]:   https://colemak.com
[lafayette]: https://qwerty-lafayette.org/
[arsenik]:   https://github.com/OneDeadKey/arsenik
