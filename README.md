# cecho.sh

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
