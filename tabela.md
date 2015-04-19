
|  FUNKCJA       |ASCI           | MARKDOWN |
| ------         |:-------------:| :------: |
| Nagłowek H     | ====lub ==H1 |          |
| Nagłowek H1    | ----lub ===H2 |   #      |
| Nagłowek H2    | ~~~~lub ====H3 |    ##    |
| Nagłowek H3    | ^^^^lub =====H4 |  ###     |
| Nagłowek H4    | ++++lub ======H5 | ####     |
|kursywa         | \_tekst\_     |\*tekst\*  \_tekst\_|
|pogrubienie     | \*\*tekst\**   |\*\*tekst\** |
|Przekreślenie   |               | \~\~tekst\~~|
|zacienienie     | \+test\+      | \`\`tekst`` |
|Lista numerowana|   . Jeden     | 1. Jeden |
|Lista "kropkowana"| - Jeden     | - punkt (* lub +)|
|Podlista numerowana|.. podpunkt(ile .. taki stopień)| ⟶ 1. podpunkt|
|Podlista "kropki"  |\* podpunkt(ile \*** taki stopień)| ⟶ - podpunkt(* lub +)|
|Linki          |http://adres.pl[nazwa] |\[nazwa](www.adres.pl)|
|Link z "opisem"|http://strona.com [opis]  |\[nazwa](www.adres.pl"opis")|
|Link "przypis"|brak |teskt\[1]  \[1]:www.adres.pl|
|Obrazek| \image:obrazek.jpg[tekst] |\!\[alt text](https://adres.pl "Tytuł,nazwa")|
|Cytat|[quote, autor, tutuł]  |\>cytat|

********************

<html lang="pl">
<head>
<meta charset="utf-8">
</head>
<body>
<table border="1">
<caption align="top">Tabelka porównująca notacje(html).
<tr bgcolor="#CC66FF"><th>FUNKCJA <th> ASCII <th> MARKDOWN 
<tr><th> Nagłowek H <td> ====== lub ==H <td>  brak 
<tr><th> Nagłowek H1 <td> ----- lub ===H1 <td> #
<tr><th> Nagłowek H2 <td> ~~~~~ lub ====H2 <td> ##
<tr><th> Nagłówek H3 <td> ^^^^^ lub =====H3 <td> ###
<tr><th> Nagłowek H4 <td> +++++ lub ======H4 <td> ####
<tr><th> Kursywa <td> _tekst_ <td> *teskt* lub _tekst 
<tr><th> Pogrubienie <td> **teskt** <td> **tekst**
<tr><th> Przekreślenie <td> brak <td> ~~tekst~~
<tr><th> Zacienienie <td> +tekst+ <td> ``teskt``
<tr><th> Lista numerowana <td> .jeden .dwa <td> 1. jeden 2. dwa 
<tr><th> Lista punktowana <td> *jeden **dwa <td> *jeden (lub - +)
<tr><th> Podlista numerowana <td> ..podpunkt (ile ... taki stopień) <td> [tab] 1. podpunkt
<tr><th> Podlista punkty <td> * podpuntk (ile ** taki podpunkt) <td> [tab] - podpunkt (* lub +)
<tr><th> Link <td> http://adres.pl [nazawa] <td> [nazwa](www.adres.pl)
<tr><th> Link z opisem <td>http://strona.com [opis]  <td> [nazwa](www.adres.pl"opis")
<tr><th> Link "przypis"<td>brak <td>teskt\[1]  \[1]:www.adres.pl
<tr><th> Obrazek<td> \image:obrazek.jpg[tekst] <td>![alt text](https://adres.pl "Tytuł,nazwa")
<tr><th> Cytat<td> [quote, autor, tutuł]  <td>>cytat
</table>
</body>
</html>
