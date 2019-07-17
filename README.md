# cecho.sh

colored echo for bash

## quickstart

```
{
  git clone https://github.com/temptemp3/cecho.sh.git
  ( cd cecho.sh ; git clone https://github.com/temptemp3/sh2.git -b 190717 )
  chmod +x cecho.sh/cecho.sh
  cecho() { _(){ ${1}/${1} ${@:2} ; } ; _ ${FUNCNAME}.sh ${@} ; }
  cecho green green
}
```

## output

```
Cloning into 'cecho.sh'...
remote: Enumerating objects: 20, done.
remote: Counting objects: 100% (20/20), done.
remote: Compressing objects: 100% (16/16), done.
remote: Total 20 (delta 5), reused 8 (delta 2), pack-reused 0
Unpacking objects: 100% (20/20), done.
Cloning into 'sh2'...
remote: Enumerating objects: 34, done.
remote: Counting objects: 100% (34/34), done.
remote: Compressing objects: 100% (30/30), done.
remote: Total 428 (delta 10), reused 15 (delta 4), pack-reused 394
Receiving objects: 100% (428/428), 113.41 KiB | 0 bytes/s, done.
Resolving deltas: 100% (243/243), done.
 green
```
