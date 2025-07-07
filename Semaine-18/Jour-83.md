# Objectifs journaliers

## Vendredi 04/07/2025 :

### Les Tests End-to-End (E2E)

- [x] Comprendre l'objectif : simuler un parcours utilisateur complet dans l'application, depuis le navigateur
- [x] Comprendre la place des tests E2E dans la pyramide des tests (moins nombreux, plus lents, mais cruciaux)
- [x] Identifier les scénarios utilisateurs critiques à couvrir par des tests E2E

### Découverte et pratique d'un outil de test E2E

- [x] **Outils communs (cross-technologies) :** Playwright, Cypress
- [x] Installer et configurer un outil de test E2E dans son projet
- [x] Utiliser le "Test Recorder" de l'outil pour générer un premier script de test
- [x] Apprendre les commandes de base :
  - [x] Naviguer vers une page (`goto`, `visit`)
  - [x] Localiser des éléments (`getByRole`, `locator`, `get`)
  - [x] Interagir avec les éléments (`click`, `fill`, `type`)
  - [x] Écrire des assertions sur l'état de la page (`expect(page).toHaveTitle`, `expect(element).toBeVisible`)


### Exercice Pratique

- [x] Écrire un test E2E pour un scénario simple d'un ancien projet (ex: se connecter, voir une page, se déconnecter)
- [x] Exécuter le test en mode "headed" (avec interface graphique) et "headless" (sans)
