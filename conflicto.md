En este archivo explicaré cómo se solucionó el conflicto al fusionar
2 ramas en las que tienen una línea con contenido distinto 

Cuando haces el _merge_ entre ambas ramas, te saldrá el siguiente mensaje
``Auto-merging notas.md``
``CONFLICT (content): Merge conflict in notas.md``
``Automatic merge failed; fix conflicts and then commit the result.``

Justo después en el archivo saldrán las líneas de ambas ramas una detrás de otra
junto con unos símbolos <<<<<<<<<< ======== >>>>>>>>>>, los cuáles debemos de borrar
para que solo salga el mensaje que queremos que salga al final