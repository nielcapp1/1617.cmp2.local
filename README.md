# 1617.cmp2.local

Crossmedia Publishing II
========================

```
cmp.local/
├── wordpress/
├── data/
├── scripts/
└── README.md
```

Benodigdheden
-------------

Installeer (of update):

 1. [Artevelde Dotfiles](http://www.gdm.gent/dotfiles/)
 2. [Artestead](http://www.gdm.gent/artestead/)

Installatie
-----------

Maak een map `Code` in je thuismap.

```
$ h
$ mkdir Code
$ c
$ git clone http://github.com/gdmgent/1617.cmp2.local
```

### WordPress

Ga naar de projectmap, installeer en configureer de server en start die daarna op.

```
$ cmp2
$ artestead make --type wordpress
$ vu && vss
vagrant@cmp$ composer global require consolidation/cgr
vagrant@cmp$ cgr wp-cli/wp-cli
vagrant@cmp$ dos2unix ~/cmp2.local/scripts/*
vagrant@cmp$ ~/cmp2.local/scripts/db_init.sh 
vagrant@cmp$ ~/cmp2.local/scripts/wp_install_cli.sh
vagrant@cmp$ ~/cmp2.local/scripts/wp_install.sh
vagrant@cmp$ exit
$ _
```

URI's
-----

 - <http://www.cmp2.local>
 - <http://www.cmp2.local/admin>
