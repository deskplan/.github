<p align="center">
  <img src="https://raw.githubusercontent.com/deskplan/brand/main/logo.svg" alt="DeskPlan" width="112" height="112">
</p>

<h1 align="center">DeskPlan</h1>

<p align="center">
  <em>Gestion du personnel et des bureaux des laboratoires —<br>
  une API Go, un client web et une application macOS native, à parité.</em>
</p>

<p align="center">
  <a href="https://deskplan.github.io/">Site</a> ·
  <a href="https://deskplan.github.io/docs/">Documentation</a> ·
  <a href="https://github.com/deskplan/brand">Marque</a>
</p>

---

**DeskPlan** aide les laboratoires (CPHT, CMLS…) à tenir à jour **qui travaille où** : annuaire du personnel, plans de bureaux interactifs, arrivées et départs, taux d'occupation — le tout **multi-laboratoire**, avec des données strictement cloisonnées par labo.

Une même API sert **deux clients à parité** : un client web et une application macOS native.

## Composants

| Dépôt | Rôle | Stack |
|---|---|---|
| **server-go** | API + logique métier + service des clients | Go · Huma v2 · PostgreSQL |
| **web** | Client web | SvelteKit · TypeScript · Tailwind |
| **macos** | Application de bureau native | SwiftUI |
| [**docs**](https://github.com/deskplan/docs) | Documentation | MkDocs Material → [Pages](https://deskplan.github.io/docs/) |
| [**brand**](https://github.com/deskplan/brand) | Logo, couleurs, iconographie | SVG · PNG |

## Fonctionnalités

- **Annuaire** du personnel (statuts, groupes, nationalités, dates d'arrivée/départ).
- **Plans de bureaux** interactifs : affectation par glisser-déposer, occupation, places libres à une date.
- **Checklists** d'arrivée et de départ, journal d'audit des modifications.
- **Interroger** : questions en langage naturel traduites en requêtes (IA), cloisonnées par labo.
- **Import / export Excel** du personnel, modèle fourni.
- **Authentification** LDAP ou comptes locaux, 2FA (clé de sécurité / code e-mail), rôles fins par labo.

## Accès

L'instance de production est réservée aux laboratoires participants. La documentation d'utilisation et d'administration est publique : **<https://deskplan.github.io/docs/>**.

<sub>Développé par l'<strong>IDCS — École polytechnique</strong>.</sub>
