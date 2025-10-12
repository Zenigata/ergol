+++
title = "Installation"
aliases = ["lts"]

[params]
cssSheets = ["/css/keebs.css"]
jsModules = ["/js/x-keyboard.js"]
jsScripts = ["/js/keebs.js"]
footer = "propulsé par [x-keyboard](https://onedeadkey.github.io/x-keyboard)"
+++

{{<x-keyboard name="Ergo‑L" data="ergol" class="odk">}}


Téléchargement
--------------------------------------------------------------------------------

### Pilotes nomades : [ergol_nomade.zip][]

Une archive ZIP contenant les pilotes ne nécessitant pas de droits
d’administration, qui peuvent fonctionner depuis une clé USB. (Pour tous les
systèmes.)

### Windows : [ergol_kbd.exe][]

Exécuter l’installeur et relancer la session. La disposition de clavier
apparait dans la barre de langues (indicateur de la barre des tâches).

### Windows – méthode alternative avec pilote signé : [ergol_msklc.zip][]

MSKLC (Microsoft Keyboard Layout Creator) permet d’avoir des pilotes mieux
reconnus car signé par Microsoft, mais pour lequel, après installation, il
faudra ajouter manuellement la disposition clavier dans la liste des
dispositions disponibles.

Après téléchargement, dézipper l’archive au complet et exécuter `setup.exe`.
Suivre les instructions d’installation et fermer puis relancer la session
utilisateur.

<details>

<summary>Ajouter la disposition installée dans la liste (Windows 10)</summary>

1. Dans le menu Démarrer, rechercher « Modifier les paramètres de langue et de
   clavier »

   ![](windows10/windows10_1.webp)
  
2. Cliquer sur « Options » sur « Français »

   ![](windows10/windows10_2.webp)

3. « Ajouter un clavier »
  
   ![](windows10/windows10_3.webp)

4. Il devrait y avoir Ergo‑L dans la liste, cliquer dessus
  
   ![](windows10/windows10_4.webp)

5. Ergo‑L est maintenant ajouté. On devrait voir en bas à droite une icône
   « FRA » ou « FRA FR » pour choisir le clavier s’il y en a plusieurs dans la
   liste

   ![](windows10/windows10_5.webp)

</details>

### macOS : [ergol.keylayout][]

Enregistrer dans `/Library/Keyboard Layouts` et relancer la session.  La
disposition de clavier est disponible dans les préférences sous « Clavier »,
« Méthodes de saisie », `+` (ajouter une nouvelle disposition), et enfin «
Autres ».

On peut aussi l’enregistrer dans `~/Library/Keyboard Layouts`
(pour le seul utilisateur courant), mais la disposition ne sera pas
active au login.

Il est possible (et recommandé) d’utiliser [Karabiner][]
pour [inverser les touches](karabiner_settings.png) [⌘ Command]{.kbd}
et [⌥ Option]{.kbd} à droite, afin d’accéder plus facilement à la couche
de symboles.

### Linux : [ergol.xkb_symbols][]

Ergo‑L est déjà inclus dans toutes les distributions Linux dotées de `xkeyboard-config`
en [version 2.42 ou ultérieure](https://repology.org/project/xkeyboard-config/versions),
ce qui inclut notamment Arch, Debian Trixie/Sid, Fedora Rawhide, Gentoo, Manjaro
Testing/Unstable, OpenMandriva Rolling/Cooker, OpenSUSE Tumbleweed, Slackware
Current, Ubuntu 24.10.
<!-- Il a aussi été inclus dans Ubuntu 24.04 LTS (rétro-portage). -->

Pour les autres distributions, copier ce pilote dans `xkb/symbols/custom` :

```bash
sudo wget -O ${XKB_CONFIG_ROOT:-/usr/share/X11/xkb}/symbols/custom \
https://github.com/Nuclear-Squid/ergol/releases/download/ergol-v1.0.0/ergol.xkb_symbols
```

La disposition de clavier ainsi installée est disponible dans le gestionnaire de
préférences du bureau sous un nom générique (« custom layout », « disposition
personnalisée », etc.). Sous XOrg on peut aussi l’activer directement en ligne
de commande :

```bash
setxkbmap custom
```

D’autres méthodes d’installation sont possibles, en passant le [fichier
source][] à [XKalamine][].

### Aide-mémoire : [cavalier.pdf][]

Une aide pour apprendre la dispo. À imprimer, plier et placer sur son bureau !


Variante en A (« <i lang="en">angle mod</i> »)
--------------------------------------------------------------------------------

![](angle_mod.svg)

Des pilotes incluant l’[angle mod][] seront proposés. Il est d’ores et déjà
possible d’appliquer cet angle mod et bien d’autres fonctionnalités via
[kanata][] et la configuration [Arsenik][].


Résolution de problèmes
--------------------------------------------------------------------------------

Vous avez des questions ou des problèmes avec les pilotes ? Consultez notre
[FAQ] !


Astuces
--------------------------------------------------------------------------------

### Disposition clavier par défaut sur Windows

1. Rechercher dans le menu Démarrer « Paramètres avancés de clavier »
2. Dans « Remplacer la méthode d’entrée par défaut » : choisir sa dispo préférée
  dans le menu déroulant


Licence
--------------------------------------------------------------------------------

[WTFPL](http://wtfpl.net/) – Do What the Fuck You Want to Public License.


[fichier source]:    /keymaps/fr/ergol.toml
[cavalier.pdf]:      cavalier.pdf
[ergol_nomade.zip]:  https://github.com/Nuclear-Squid/ergol/releases/download/ergol-v1.0.0/ergol_nomade.zip
[ergol_kbd.exe]:     https://github.com/Nuclear-Squid/ergol/releases/download/ergol-v1.0.0/ergol_kbd.exe
[ergol_msklc.zip]:   https://github.com/Nuclear-Squid/ergol/releases/download/ergol-v1.0.0/ergol_msklc.zip
[ergol.keylayout]:   https://github.com/Nuclear-Squid/ergol/releases/download/ergol-v1.0.0/ergol.keylayout
[ergol.xkb_symbols]: https://github.com/Nuclear-Squid/ergol/releases/download/ergol-v1.0.0/ergol.xkb_symbols
[XKalamine]:         https://github.com/OneDeadKey/kalamine#xkalamine
[Karabiner]:         https://karabiner-elements.pqrs.org

[Arsenik]:           /claviers/arsenik/
[kanata]:            https://github.com/jtroo/kanata
[angle mod]:         https://colemakmods.github.io/ergonomic-mods/angle.html
[FAQ]:               /ressources/faq
