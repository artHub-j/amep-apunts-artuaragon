# <img src="../assets/UPClogo.png" alt="Logo_UPC svg" width="40" height="40"> amep-apunts-artuaragon | TEMA 2 | DL 8 ABRIL 2024 | 

## Index

| RESUMS |                                    T1                                     |                                  T2                                   | IA Generativa | Agile QUABU
| :---: | :-----------------------------------------------------------------------: | :-------------------------------------------------------------------: | :-: |:-: |
| Link  | [<img src="../assets/linkicon.png" alt="link" width="40" height="40">](https://github.com/artHub-j/amep-apunts-artuaragon/blob/main/APUNTS/T1-apunts.md) | [<img src="../assets/linkicon.png" alt="link" width="40" height="40">](https://github.com/artHub-j/amep-apunts-artuaragon/blob/main/APUNTS/T2-apunts.md)|[<img src="../assets/linkicon.png" alt="link" width="40" height="40">](https://github.com/artHub-j/amep-apunts-artuaragon/blob/main/APUNTS/IA_Generativa-apunts.md)|[<img src="../assets/linkicon.png" alt="link" width="40" height="40">](https://github.com/artHub-j/amep-apunts-artuaragon/blob/main/APUNTS/Agile_QUABU-apunts.md) |

# Conceptes basics de les metodologies Agile

## SCRUM:
- Def.:
       Metodologia agil per la gestio i desenvolupament de projectes. Basada en principis iteratius i incrementals. Treball dividit en cicles curts (Sprints).

```mermaid
graph TD;
    A[Fases]-->Incepcio;
    A-->Desenvolupament;
```
### - INCEPCIO:

- IDEA GENERAL, FRONTERA.
- Identificar PARTS IMPLICADES (stakeholders).
- Determinar GRUPS principals de FUNCIONALITATS.
- Identificar HISTORIES D'USUARI.
- Preparar ENTRON DE TREBALL.
- Visualitzar ARQUITECTURA TECNICA
- Estimar COST i fer PLANIFICACIO TEMPORAL.
- Identificar RISCOS.

```mermaid
graph TD;
    A[Idea General del Sistema]-->B[Prodcut Box];
    A-->C[Elevator Pitch];
    A-->Mock-Ups;
    
    E[Frontera del Sistema]-->NOT-list;

    G[Parts Implicades]-->identificacio;
    G-->Registre;

    F[Grups de Funcionalitats]-->Epiques;
    F-->H[Relacio amb parts implicades];

```

```mermaid
graph TD;
    A[Histories d'usuari]-->Concepte;
    A-->identificacio;
    A-->B[Emmagatzematge en backlog];

    C[Arquitectura del Sistema]-->D[Descripcio d'alt Nivell];

    E[Gestio del risc]-->F[Ennumeracio d'amenaces]

    G[Pla de Prjecte]-->H[Primera Release];
```

- AMEP: 1 Release, 1+3 Iteracions, 14 setmanes, equip de 6-8 persones, 0 eur.

### - DESENVOLUPAMENT:

- Dividit per Iteracions (Sprints).
- Objectiu que defineix l'abast d'increment.
- Backlog (Conte H.U. amb metadades com esforc, temps, etc)

```mermaid
graph TD;
    A[Backlog]-->B[Product Backlog: Requisits de tot el Producte];
    A-->C[Sprint Backlog: Requsits de cada Iteracio];
```
- Histories d'Usuari (HU) - INVEST.
  - Valorades amb Story Points (Mesura d'esforç; XS, S, M, L, XL / 5, 8, 13, 21, etc).
  - Planning Poker (Joc col.laboratiu per prioritzar HU).
  - DoD - Definition of Done (Condicions per considerar una HU com feta).
  - Criteris d'acceptacio.

```mermaid
graph TD;
    A[INVEST:]-->I[I - Independent: Implementacio no depen de cap altra HU]-->N[N - Negotiable: amb el client]-->V[V - Valuable: Tota HU aporta valor]-->E[E - Estimable: Estimacio esforç possible]-->S[S - Small: Finalitza en una It.]-->T[T - Testable: Es pot provar si la implementacio ha anat bé]

```

- Cerimònia:
  
    <img src="../assets/CerimoniaAgil.png">

    - Planning Meeting: definir objectius iteracio (Creació BackLog itreacio).
    - Daily Scrum: Reunions diaries (breu 15 min.) per posar en comu el que s'està fent durant l'iteració.
    - Sprint Review: penultim pas de per finalitzar l'iteració, reunió per presentar el treball fet a l'Stakeholder (Dimecres LAB amb Xavi). Actualitzar Backlog de producte, comentar problemes etc.
    - Retrospective Meeting: ultim pas de l'iteració; Que va anar be, que es pot millorar i que es millorarà.
  
- Tècniques: 
  - Gestio del progrès.
    - Velocitat (quantitat de treball/punts fets en la iteració), BurndownChart (release: punts historia restants/iteració: punts historia completats, actulaitzat diariament.)