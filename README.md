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
$ cd 1617.cmp2.local
$ artestead make --type wordpress --ip 192.168.10.45
$ vu
& vss
vagrant@1617:~/1617.cmp2.local$ dos2unix ~/1617.cmp2.local/scripts/*
vagrant@1617:~/1617.cmp2.local$ ~/1617.cmp2.local/scripts/db_init.sh 
vagrant@1617:~/1617.cmp2.local$ ~/1617.cmp2.local/scripts/wp_install_cli.sh
vagrant@1617:~/1617.cmp2.local$ ~/1617.cmp2.local/scripts/wp_install.sh
vagrant@1617:~/1617.cmp2.local$ exit
$ _
```

URI's
-----

 - <http://www.1617.cmp2.local>
 - <http://www.1617.cmp2.local/admin>
