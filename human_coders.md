#Public visé

Cette formation s’adresse aux développeurs d’applications Rails débutant dans l'écriture de tests automatisés.

#Pré-requis :

* développement d'applications web avec le framework Ruby on Rails
* (Les participants amèneront leur ordinateur portable avec un environnement de développement Rails et ruby 1.9.3)

#Objectifs pédagogiques :

* Ecrire des Tests lisibles, maintenables et rapides
* Apprendre à utiliser et configurer le framework de tests RSpec
* Etre capable d'identifier les classes et couches applicatives à tester en priorité
* Connaître les principes du Développement Piloté par les Tests (TDD en anglais)

#Contenus de formation :

* "Bootstrap": Installer l'application web Ruby on Rails qui va servir de support pour les exercices
* Introduction aux tests
  * Comprendre la valeur des Tests Unitaires et pourquoi en écrire
  * Connaître la différence entre Tests Unitaires et Tests d'Acceptance (cucumber)
* Introduction au Framework de Tests [RSpec](https://www.relishapp.com/rspec)
  * Apprendre les qualités d’un bon Test Unitaire
  * Configurer les "Hooks" (before, after) pour chaque suite de tests et/ou test
  * Apprendre les assertions d'égalité: equal, eql, eq
  * Apprendre les assertions raise_error
  * Découvrir le sucre syntaxique de RSpec
* Boite à outils
  * Speeder l'exécution de tests avec [Spork](https://github.com/sporkrb/spork)
  * Automatiser l'exécution de tests avec [Guard](https://github.com/guard/guard)
  * Vérifier la couverture de tests avec [SimpleCov](https://github.com/colszowka/simplecov)
* Tester les librairies (lib)
* Tester les Modèles
  * Configurer use_transactional_fixtures
  * Construire des données de test avec [FactoryGirl](https://github.com/thoughtbot/factory_girl)
  * Garder une DB de tests "clean" avec [DatabaseCleaner](https://github.com/bmabey/database_cleaner)
  * Tester la logique métier de votre application
  * Tester les named scope et finders
* Tests d'intégration avec [capybara](https://github.com/jnicklas/capybara)
  * Tester les Pages sans javascript avec le driver rack_test
  * Tester votre application web 2.0 Ajax avec le driver [webkit](https://github.com/thoughtbot/capybara-webkit)
  * Déboguer avec capybara
* Introduction aux Mocks objects avec [rspec-mock](https://www.relishapp.com/rspec/rspec-mocks/docs)
  * Comprendre la différence entre "Stubs", "Mocks" et "Test Doubles"
  * Stubber un service de géo-localisation
  * Stubber les dates et heures
  * Stubber avec FactoryGirl
  * Vérifier le comportement d'une dépendance de la classe testée avec les Mocks
* Tester les Mailers avec [email_spec](https://github.com/bmabey/email-spec)
* Tester les routes
* Tester les [Controlleurs](http://solnic.eu/2012/02/02/yes-you-should-write-controller-tests.html)
* Tester les Helpers

#Evaluation des acquis de la formation :

Durant la journée de formation, le stagiaire doit écrire les tests d'une application Rails.

#Qualité du/des formateurs :

Ingénieur développeur ruby, il possède 10 ans d'expériences en Tests Unitaires et 7 ans en TDD.
Il a donné de nombreuses conférences sur le sujet: Conferencia Rails 2006 (Madrid), XP Days France 2008, Continous Integration and Testing conference Amsterdam 2008, Paris on Rails 2007 et 2008 ainsi que Ruby Camp Lyon 2009 et 2010.

Voir http://www.slideshare.net/garnierjm
