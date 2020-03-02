# System-Programmierung
## Hands-on zu Lektion 2
Für Slides und Code Beispiele, siehe [Lektion 2](../../../fhnw-syspr/blob/master/02/README.md)

> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Erstellen Sie eine persönliche Kopie, mit diesem GitHub Classroom Link](https://classroom.github.com/a/ojMbVDKD).*

### a) Heap Struct, 15'
* In [struct.c](https://github.com/tamberg/fhnw-syspr/blob/master/02/struct.c) wird ein Struct auf dem Stack alloziert, mit return zurückgegeben und dabei "by value" kopiert.
* Schreiben Sie ein Programm *my_struct_v2.c*, das für *create_struct* Pointer und [malloc](http://man7.org/linux/man-pages/man3/malloc.3.html) verwendet:<pre>
    Point *create_point(int x, int y);</pre>
* Passen Sie den restlichen Code entsprechend an, der Compiler gibt Ihnen dabei nützliche Hinweise.

### b) Linux Betriebssystem, 5'
* Aus welchen Teilen besteht das Linux Betriebssystem?
* Suchen Sie online nach schematischen Darstellungen.
* Welche Darstellungsweise finden Sie besonders klar?
* Was sind die jeweiligen Aufgaben einzelner Teile?

### c) Kilo.c, 15'
* Analysieren Sie den Source Code dieses Programms:<pre>
    https://github.com/antirez/kilo/blob/master/kilo.c</pre>
* Kompilieren Sie das Programm und benutzen Sie es.
* Wie verwaltet das Programm eingegebenen Text?
