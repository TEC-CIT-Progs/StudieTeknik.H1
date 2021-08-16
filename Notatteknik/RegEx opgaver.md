# 1. RegEx opgaver

__Kopier svarene ind i en tekst fil.__
## 1.1. Check match `/ab+c?/`

Hvilke af følgende strenge matcher mønstret `/ab+c?/` ?

1. abc
2. ac
3. abbb
4. bbc

## 1.2. Check match `/a.[bc]+/`

Hvilke af følgende strenge matcher mønstret `/a.[bc]+/` ?

1. abc
2. abbbbbbbb
3. azc
4. abcbcbcbc
5. ac
6. asccbbbbcbcccc

## 1.3. Check match `/abc|xyz/`

Hvilke af følgende strenge matcher mønstret `/abc|xyz/` ?

1. abc
2. xyz
3. abc|xyz

## 1.4. Check match `/[a-z]+[\.\?!]/`

Hvilke af følgende strenge matcher mønstret `/[a-z]+[\.\?!]/` ?

1. battle!
2. Hot
3. green
4. swamping.
5. jump up.
6. undulate?
7. is.?

## 1.5. Check match `/[a-zA-Z]*[^,]=/`

Hvilke af følgende strenge matcher mønstret `/[a-zA-Z]*[^,]=/` ?

1. Butt=
2. BotHEr,=
3. Ample
4. FIdD1E7h=
5. Brittle =
6. Other.=

## 1.6. Check match `/[a-z][\.\?!]\s+[A-Z]/`

Hvilke af følgende strenge matcher mønstret `/[a-z][\.\?!]\s+[A-Z]/` ?

1. A. B
2. c! d
3. e f
4. g.  H
5. i? J
6. k L

## 1.7. Check match `/<[^>]+>/`

Hvilke af følgende strenge matcher mønstret `/<[^>]+>/` ?
```
   1. <an xml tag>
   2. <opentag><closetag>
   3. </closetag>
   4. <>
   5. <with attribute="77">
```


De næste opgaver løses på https://extendsclass.com/regex-tester.html

## 1.8. Drengene

I teksten

    Johanne, Lisbeth, Jacob, Katrine, Mark, Finn, Charlotte, Mette, og Lars

Find alle drengene (_vink_: brug `m1|m2|m3 ... `)

## 1.9. Pigerne

    Liselotte, Charlotte, Pernille og Lotte

Lav et find pigerne der slutter på `Lotte` eller `lotte`.
(_vink_: første del af navnene er tegn i et ord; `\w`)


I følgende opgaver, brug teksten:

    id,firstname,lastname,phone,email,birthday
    100,Annaliese,Schenck,32597428,Annaliese.Schenck@yopmail.com,1994-01-07
    101,Shell,Kelula,15054791,Shell.Kelula@yopmail.com,1969-12-15
    102,Maud,Rocray,36763446,Maud.Rocray@yopmail.com,1995-04-19
    103,Vevay,Berriman,23301445,Vevay.Berriman@yopmail.com,1980-01-27
    104,Nyssa,Hollingsworth,24347599,Nyssa.Hollingsworth@yopmail.com,1979-11-22
    105,Donnie,Mathilde,31376355,Donnie.Mathilde@yopmail.com,1987-03-10
    106,Grier,Winthorpe,26045109,Grier.Winthorpe@yopmail.com,2003-05-08
    107,Aigneis,Suanne,12512945,Aigneis.Suanne@yopmail.com,1984-04-09
    108,Alyssa,Harriman,72849369,Alyssa.Harriman@yopmail.com,2000-05-03
    109,Rosanne,Simmonds,57537559,Rosanne.Simmonds@yopmail.com,1995-10-11
    110,Tracey,Sasnett,74458416,Tracey.Sasnett@yopmail.com,1978-07-21
    111,Olwen,Raychel,44043492,Olwen.Raychel@yopmail.com,1961-07-18
    112,Ardys,Ferino,21962099,Ardys.Ferino@yopmail.com,1964-04-22
    113,Augustine,Travax,20167180,Augustine.Travax@yopmail.com,1969-05-25
    114,Pamella,Fredi,55063798,Pamella.Fredi@yopmail.com,1965-12-09
    115,Basia,Halsey,43863518,Basia.Halsey@yopmail.com,1982-05-02
    116,Delilah,Clara,60605026,Delilah.Clara@yopmail.com,1962-02-16
    117,Fawne,Drisko,80694549,Fawne.Drisko@yopmail.com,1997-11-22
    118,Edith,Fulmer,14130960,Edith.Fulmer@yopmail.com,2001-01-06
    119,Agathe,Kalinda,81216551,Agathe.Kalinda@yopmail.com,1963-03-20
    120,Roseline,Cyrie,76916797,Roseline.Cyrie@yopmail.com,2003-08-28


## 1.10. Født i 1995

Hvor mange er født i 1995

## 1.11. Omvendt email

Alle brugerne har fået oprettet emails hvor deres fornavn står før efternavnet. Det svarer _ikke_ til den formelle form. 
Byt om så efternavnet står forrest!

## 1.12. Landekode

Telefonnumrene mangler landekode. Tilføj `+45` til telefonumrene.

## 1.13. Måneder med navn

Ud skift tallet for måned i fødselsdagene så der står tre bogstaver for den engelske forkortelse af månedens navn. `05` => `may`, `12` => `dec`.

## 1.14. Danske telefonnumre

I Danmark har alle telefonnumre 8 cifre! Men de kan skrives forskelligt, ved at adskille forskelligt. 
Lav søg-erstat-mønster som genkender 8-cifrede numre uanset hvordan der er mellemrum.
Godkend også numre med `+45`. Tilføj `+45 ` (og et mellemrum) hvis det mangler.

Hvilke danske numre er ikke på 8-cifre?
Hvad med Fæøerne og Grøndland?

## 1.15. email

Kan du lave et møster der genkender _alle_ gyldige emails?

Hvilke regler gælder for domænenavne?
Hvilke for brugernavne?

    smag@tec.dk
    svend.bendt@post.tele.dk
    forfatter-knud-romer@gyldendal.dk
    klumb1@chef.dk

find selv flere, anderledes varianter


