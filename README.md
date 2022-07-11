<h2>Kanonov algoritam za množenje matrica</h2>

<h3>Opis problema:</h3>

Množenje matrica A i B dimenzija n x n
<h3>Opis algoritma:</h3>

Korak 1: Početni korak algoritma je šifrovanje matrica na sledeći način. Redove matrice A šiftujemo u levo za 0 do n - 1 počevši od reda 0 do reda n - 1, ovim procesom dobijamo matricu A1. Kolone matrice B šiftujemo na gore za 0 do n - 1 počevši od od kolone 0 do kolone n - 1, ovim procesom dobijamo matricu B1. 

Korak 2: Množimo matrice A1 i B1 da bi dobili matricu C1 na sledeći način C1[i][j] = A1[i][j] * B1[i][j]

Korak 3:  Šiftujemo matricu A1 za 1 u levo i matricu B1 za 1 na gore kako bi dobili matrice A2 i B2.

Korake 2 i 3 ponavljamo n - 1 puta i na kraju konacnu matricu C dobijamo sabiranjem matrica C1 + C2 + ... + Cn

<h3>Izabrana implementacija:</h3>

Opisani algoritam biće implemenitran u vidu sekvencijalnog i paralelizovanog rešenja u programskom jeziku python.
