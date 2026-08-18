| Hallazgo | Dónde estaba | Técnica de Git | Comando exacto | Referencia |
|---|---|---|---|---|
| FRAG-01 | Archivo borrado en la rama principal de la cinta | Recuperar archivo de un commit anterior a su borrado | `git show f260559~1:bitacora/frag-01.txt` | `f260559` |
| FRAG-02 | Mensaje de un tag anotado (no es rama) | Inspeccionar el objeto tag directamente | `git cat-file -p refs/tags/respaldo/pre-incidente` | `7af37c1` |
| Glifo (sello.svg) | Archivo en el commit apuntado por el tag de respaldo | Leer archivo desde un commit específico | `git show 66f368e9:assets/sello.svg` | `66f368e` |
