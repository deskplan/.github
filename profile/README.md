<p align="center">
  <img src="https://raw.githubusercontent.com/deskplan/brand/main/logo.svg" alt="DeskPlan" width="96" height="96">
</p>

<h1 align="center">DeskPlan</h1>

<p align="center">Gestion du personnel et des bureaux des laboratoires.</p>

<p align="center">
  <a href="https://deskplan.github.io/">Site</a> ·
  <a href="https://deskplan.github.io/docs/">Documentation</a> ·
  <a href="https://github.com/deskplan/brand">Marque</a>
</p>

---

DeskPlan tient à jour, pour un ou plusieurs laboratoires, **qui travaille où** : annuaire du personnel, plans d'occupation des bureaux, arrivées et départs. Les données sont **cloisonnées par laboratoire**.

Une même API sert deux clients maintenus à parité : un client web et une application macOS native.

## Dépôts

| Dépôt | Rôle | Technologies |
|---|---|---|
| **server-go** | API et logique métier | Go · Huma v2 · PostgreSQL |
| **web** | Client web | SvelteKit · TypeScript |
| **macos** | Application de bureau | SwiftUI |
| [**docs**](https://github.com/deskplan/docs) | Documentation ([en ligne](https://deskplan.github.io/docs/)) | MkDocs Material |
| [**brand**](https://github.com/deskplan/brand) | Logo, couleurs, iconographie | SVG · PNG |

## Fonctionnalités

- Annuaire du personnel : statut, groupe, nationalités, dates de contrat.
- Plans des bureaux : affectation, taux d'occupation, places libres à une date.
- Arrivées et départs : listes de tâches, journal des modifications.
- Interrogation des données en langage naturel, cloisonnée par laboratoire.
- Import et export Excel du personnel.
- Authentification LDAP ou comptes locaux, double authentification, rôles par laboratoire.

## Accès

L'instance de production est réservée aux laboratoires participants. La documentation d'utilisation et d'administration est publique : **<https://deskplan.github.io/docs/>**.

---

<p align="center">
  <img src="https://raw.githubusercontent.com/deskplan/brand/main/idcs-logo.png" alt="IDCS Research Facilities" height="40">
</p>
<p align="center"><sub>Développé par l'<strong>IDCS</strong> — École polytechnique.</sub></p>
