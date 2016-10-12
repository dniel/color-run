# color-run
When I was a little kid, I loved typing in this short program on all Commodore 64 in the electronics shops making the screen do the famous C64 color loop used while loading tapes..

It was one of the first programs I wrote, when I was just 12 years old.
I quikly typed it on all machines and ran to observer..

```REALbasic
10 FOR I = 0 TO 15
20 POKE 53280, I
30 POKE 53281, I+1
40 NEXT
50 GOTO 10
```
