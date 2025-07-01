# Objectifs journaliers

## Mardi 24/06/2025 :

### Les Tests Unitaires (TU)
- [x] Comprendre l'objectif des tests unitaires : tester la plus petite partie de code (une fonction, une méthode) de manière isolée.
- [x] Savoir comment "mocker" (simuler) les dépendances externes (BDD, API, etc.) pour garantir l'isolation.
- [x] Écrire des assertions pertinentes pour valider le comportement attendu.

### Mise en pratique par technologie
- [x] **Pour tous :** Écrire des tests unitaires pour une fonction pure (ex: une fonction de calcul simple).

- [x] **Java (avec JUnit) :**
  - [x] Configurer JUnit dans un projet Maven ou Gradle.
  - [x] Utiliser les annotations `@Test`, `@BeforeEach`, `@AfterEach`.
  - [x] Utiliser une librairie de mock (ex: Mockito) pour simuler des dépendances.
  - [x] Écrire des assertions avec AssertJ ou les assertions de JUnit.

- [x] **C# (avec xUnit ou NUnit) :**
  - [x] Configurer un projet de test dans une solution .NET.
  - [x] Utiliser les attributs `[Fact]` ou `[Test]`.
  - [x] Utiliser une librairie de mock (ex: Moq) pour simuler des dépendances.
  - [x] Écrire des assertions avec FluentAssertions ou les assertions natives.

- [x] **PHP (avec PHPUnit) :**
  - [x] Configurer PHPUnit pour un projet (via `phpunit.xml`).
  - [x] Étendre la classe `TestCase`.
  - [x] Créer des mocks avec `createMock()` ou Prophecy.
  - [x] Écrire des assertions (ex: `assertEquals`, `assertTrue`).

- [x] **TypeScript (avec Jest ou Vitest) :**
  - [x] Configurer Jest ou Vitest dans un projet Node.js/frontend.
  - [x] Utiliser les fonctions `describe`, `it` (ou `test`).
  - [x] Simuler des modules ou des fonctions avec `jest.mock()` ou `vi.mock()`.
  - [x] Écrire des assertions avec `expect()`. 