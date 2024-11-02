Aquest és el disseny de base de dades relacional que inclou les entitats principals amb els seus atributs i relacions.

<img src = 1.jpg width="750" height="600">

Aquestes són les entitats:

  RECINTES
  CONCERTS
  GRUPS
  PARCEL·LES
  CARRERS
  PERSONES 
  ACCÉS

Aspectes a tenir en compte
RECINTES té com a clau primària el seu identificador, ja que cada recinte es distingeix pel seu nom. RECINTES manté una relació 1-N amb CONCERTS, ja que dins d'un recinte es poden programar diversos concerts.

GRUPS té una relació 1-N amb CONCERTS, ja que un mateix grup pot participar en múltiples concerts. Dins de GRUPS, existeix una relació recíproca N-N, ja que un grup pot fer de substitut d'un altre.

A PARCEL·LES, id_parcela és un atribut que hem afegit com a clau primària per identificar cada parcel·la de forma única. PARCEL·LES manté una relació N-1 amb CARRERS, ja que diverses parcel·les poden situar-se en un mateix carrer.
