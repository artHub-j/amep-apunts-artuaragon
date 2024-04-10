# <img src="assets/UPClogo.png" alt="Logo_UPC svg" width="40" height="40"> amep-apunts-artuaragon | TEMA 2 | DL 8 ABRIL 2024 | 

| Resums |                                    T1                                     |                                  T2                                   |
| :---: | :-----------------------------------------------------------------------: | :-------------------------------------------------------------------: |
| Link  | [<img src="assets/linkicon.png" alt="link" width="40" height="40">]([link](https://github.com/artHub-j/amep-apunts-artuaragon/blob/main/T1-apunts.md)) | [<img src="assets/linkicon.png" alt="link" width="40" height="40">](https://github.com/artHub-j/amep-apunts-artuaragon/blob/main/T2-apunts.md) |

# Conceptes basics de les metodologies Agile

## SCRUM:
- Def.:
       Metodologia agil per la gestio i desenvolupament de projectes. Basada en principis iteratius i incrementals. Treball dividit en cicles curts(Sprints).

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