# Eismo srauto duomenys

Vol (volume) – eismo intensyvumas (auto/h);
Occ (occupation) – jutiklio užimtumas (% nuo matuojamo intervalo), t. y. kokią dalį laiko, per matuojamą laikotarpį (1 val.), jutiklis buvo užimtas automobilių;
Spd (speed) – vidutinis greitis (km/h).

Po apatinio brūkšnio einantis trumpinys _orig reiškia, kad duomenys yra tiesiogiai iš sankryžų jutiklių (stulpelyje spd_orig duomenų nėra, nes jutikliai tiesiogiai greičio neskaičiuoja), o trumpinys _proc reiškia, kad duomenys yra agreguoti šviesoforų sistemos.

**Bendras ID** -->Iš eismo srauto duomenų failo lauko Name reikia „iškirpti“ sankryžos kodą – paryškintas - ig13FD**1001**_D1, o iš sankryžų koordinačių failo lauko Node taip pat reikia iškirpti sankryžos kodą – paryškintas - K**1001** Rinktinės-Kazliškių.

# Traffic detector data

Vol (volume) – traffic volume (auto/h);
Occ (occupancy) – detector occupancy (% of measuring interval) – how much time of measuring interval (1 h) detector was occupied by cars;
Spd (speed) – average speed (km/h).

Abbreviation „_orig“ means, that data is directly from intersection detectors (as intersection detectors do not count speed, there is no data in column “spd_orig”). Abbreviation „_proc“ means, that intersection detectors data is aggregate with traffic light system.

**General ID** -->you need to "cut" the intersection code - ig13FD**1001**_D1 (highlighted) from the traffic flow data file field Name, and from the intersections coordinates file field Node you need to also "cut" the intersection code - K**1001** Rinktinės-Kazliškių (highlighted).
