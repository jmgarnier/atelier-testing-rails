#Testing Rails Workshop

##Détails
###Pour qui?

Développeur qui débute dans l'écriture de tests.

###Combien ça coûte?
500 € pour la journée.

Je suis auto-entrepreneur, je ne facture pas la TVA.

###Quand?

Contactez-moi par [e-mail](http://www.workingwithrails.com/person/6331-jean-michel-garnier/enquire/new) ou sur le [google group](https://groups.google.com/forum/?fromgroups#!forum/atelier-testing-rails) pour fixer une date.

###Quel format de workshop?

* Entre 2 et 6 participants
* une journée, 7 heures de formation
* Ecriture de tests avec [RSpec](https://www.relishapp.com/rspec)

###Objectifs pédagogiques :

* Ecrire des Tests lisibles, maintenables et rapides
* Apprendre à utiliser et configurer le framework de tests RSpec
* Etre capable d'identifier les classes et couches applicatives à tester en priorité
* Connaître les principes du Développement Piloté par les Tests (TDD en anglais)

###Que préparer?

Son ordinateur portable (linux ou mac) avec [ruby set up](http://installfest.railsbridge.org/installfest/installfest)

Nous clonerons ensemble (ou via skype) le repo git de la formation et
executer le script de bootstrap pour installer toutes les dépendances de dev.

###Où?

En France, Suisse ou Belgique;) Je suis basé à Lyon.

##Agenda

* 9h00  : Accueil + petit dej offert
* 9h30  : Début de la formation
* 11h00 - 11h10 : Pause café
* 12h30 : Pause déjeuner
* 14h00 : Reprise de la formation
* 16h00 - 16h15 : Pause café - vienoiseries
* 18h00 : Fin de l'atelier. Rétrospective

### Contenus de formation :

Chaque sujet sera introduit par 1 ou 2 slides, suivi de mains dans le camboui du code.

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

##Inscription

Merci de t'inscrire en répondant à ce [sondage de 5 minutes](http://www.21croissants.com/tdd).

## Réglement

Vous pouvez payer en liquide / cheque / virement ou je peux configurer [Weezevent](http://weezevent.com) pour la CB.
Je suis auto-entrepreneur, je ne facture pas la TVA mais je peux vous faire une facture si besoin.

Payable d'avance et remboursable jusqu'à une semaine avant l'atelier.

##Questions?

Contactez-moi par [e-mail](http://www.workingwithrails.com/person/6331-jean-michel-garnier/enquire/new) ou sur le [google group](https://groups.google.com/forum/?fromgroups#!forum/atelier-testing-rails).
