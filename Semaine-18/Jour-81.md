# Objectifs journaliers

## Mercredi 02/07/2025 :

### Les Tests d'Intégration
- [x] Comprendre l'objectif : vérifier que plusieurs modules (composants, classes) fonctionnent correctement ensemble.
- [x] Différencier test d'intégration et test unitaire.
- [x] Comprendre les défis : gestion de la base de données, des services externes, etc.

### Mise en pratique par technologie
- [x] **Pour tous :** Définir une stratégie pour isoler l'environnement de test (ex: base de données en mémoire ou dédiée aux tests).

- [ ] **Java (avec Spring Test / Testcontainers) :**
  - [ ] Utiliser `@SpringBootTest` pour charger un contexte d'application.
  - [ ] Tester l'interaction entre une couche Service et une couche Repository.
  - [ ] Utiliser une base de données H2 (en mémoire) ou Testcontainers pour des tests avec une vraie BDD.

- [ ] **C# (avec ASP.NET Core Test Host) :**
  - [ ] Utiliser `WebApplicationFactory` pour démarrer l'application en mémoire.
  - [ ] Envoyer des requêtes HTTP au serveur de test avec `HttpClient`.
  - [ ] Interagir avec une base de données de test (ex: EF Core In-Memory Database ou LocalDB).

- [x] **PHP (avec Symfony WebTestCase) :**
  - [x] Étendre la classe `WebTestCase` pour les tests fonctionnels.
  - [x] Créer un client pour simuler des requêtes HTTP (`static::createClient()`).
  - [x] Interagir avec une base de données de test (ex: SQLite en mémoire).
  - [x] Utiliser le "Crawler" pour inspecter la réponse HTML/JSON.

- [ ] **TypeScript (avec NestJS et Supertest) :**
  - [ ] Utiliser `TestingModule` pour créer un environnement de test NestJS.
  - [ ] Tester des controllers en envoyant des requêtes HTTP via Supertest.
  - [ ] Interagir avec une base de données de test. 