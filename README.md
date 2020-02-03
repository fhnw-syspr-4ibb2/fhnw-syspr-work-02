# System-Programmierung
## Hands-on zu Lektion 2
Für Slides und Code Beispiele, siehe [Lektion 2](../../../fhnw-syspr/blob/master/02/README.md)

> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Prüfen Sie die vorhandenen Forks, um das Repository für Ihre Klasse zu finden.](../../network/members)*

### a) Heap Struct, 15'
* In [struct.c](https://github.com/tamberg/fhnw-syspr/blob/master/02/struct.c) wird ein Struct auf dem Stack alloziert, mit return zurückgegeben und dabei "by value" kopiert.
* Schreiben Sie ein Programm *my_struct_v2.c*, das für *create_struct* Pointer und [malloc](http://man7.org/linux/man-pages/man3/malloc.3.html) verwendet:<pre>
    Point *create_point(int x, int y);</pre>
* Passen Sie den restlichen Code entsprechend an, der Compiler gibt Ihnen dabei nützliche Hinweise.

### b) Makros (auf Papier), 5'
* Gegeben ein Makro:<pre>
    #define max(A, B) ((A) > (B) ? (A) : (B))</pre>
* Und (separat) die Funktion:<pre>
    int max(int a, int b) { return a > b ? a : b; }</pre>
* Was passiert beim folgenden Aufruf?<pre>
    int i = 1, j = 0;
    int m = max(++i, j);
* m<sub>Makro</sub> = ?, m<sub>Funktion</sub> = ?</pre>

### c) Kilo.c, 15'
* Analysieren Sie den Source Code dieses Programms:<pre>
    https://github.com/antirez/kilo/blob/master/kilo.c</pre>
* Kompilieren Sie das Programm und benutzen Sie es.
* Was macht das Programm? Gibt es extra Features?
* Was fällt Ihnen im Source Code besonders auf?
