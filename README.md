# Testing Rails Workshop

## Détails
### Pour qui?

Développeur Ruby qui débute dans l'écriture de tests.

### Combien ça coûte?
500 € / journée / personne soient **1500 €** pour les 3 jours.

### Quand?

Contactez-moi par [e-mail](mailto:jean-michel@21croissants.com) pour fixer une date.

### Quel format?

* 3 jours de formation (7h / jour):
  * 1 jour et demi de théorie avec exercices courts pour valider chaque étape
  * 1 jour et demi de pratique sur un vrai projet
* Entre 2 et 6 participants
* Ecriture de tests avec [RSpec](http://rspec.info/)
* Sur Paris, Lyon ou Annecy, formation à [La Cordée]( http://www.la-cordee.net/ )

### Objectifs pédagogiques :

J'estime qu'il faut entre 6 mois et 1 an pour être à l'aise avec les tests. L'objectif principal de cet atelier est de réduire la courbe d'apprentissage afin de bénéficier le plus rapidemment possible de la sérénité d'une bonne couverture de tests :)

* Ecrire des Tests lisibles, maintenables et rapides
* Apprendre à utiliser et configurer le framework de tests RSpec
* Etre capable d'identifier les classes et couches applicatives à tester en priorité
* Connaître les principes du Développement Piloté par les Tests (TDD en anglais)

### Que préparer?

Son ordinateur portable (linux ou mac) avec [ruby set up](http://installfest.railsbridge.org/installfest/installfest)

Nous clonerons ensemble (ou via skype) le repo git de la formation et executerons le script de bootstrap pour installer toutes les dépendances de dev.

### Où?

En France, Suisse ou Belgique. Je suis basé à Lyon.

## Agenda

* 9h00  : Accueil + petit dej offert
* 9h30  : Début de la formation
* 11h00 - 11h10 : Pause café
* 12h30 : Pause déjeuner
* 14h00 : Reprise de la formation
* 16h00 - 16h15 : Pause café - vienoiseries
* 17h00 : Fin de l'atelier. Rétrospective le dernier jour

### Contenus de formation :

Chaque sujet sera introduit par 1 ou 2 slides, suivi d'exercices simples et pratiques.

* Introduction aux tests
  * Comprendre la valeur des Tests Unitaires et pourquoi en écrire
  * Connaître la différence entre Tests Unitaires et Tests d'Acceptance (cucumber)
* Introduction au Framework de Tests [RSpec](https://www.relishapp.com/rspec)
  * Apprendre les qualités d’un bon Test Unitaire
  * Configurer les "Hooks" (before, after) pour chaque suite de tests et/ou test
  * Apprendre les assertions d'égalité: equal, eql, eq
  * Apprendre les assertions raise_error
  * Découvrir le sucre syntaxique de RSpec
* Découverte du Développement Piloté par les Tests (TDD)
* Boite à outils
  * Speeder l'exécution de tests avec [Zeus](https://github.com/burke/zeus)
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

## Inscription

Merci de me contacter par [e-mail](mailto:jean-michel@21croissants.com) ou sur le [google group](https://groups.google.com/forum/?fromgroups#!forum/atelier-testing-rails).

## A propos
Ingénieur développeur Ruby, Jean-Michel écrit des Tests depuis 2001.
Il a donné de nombreuses conférences sur le sujet : Conferencia Rails 2006 (Madrid), XP Days France 2008, Continous Integration and Testing conference Amsterdam 2008, Paris on Rails 2007 et 2008 ainsi que Ruby Camp Lyon 2009 et 2010

## Recommendations

> On s'amuse et on code, c'est presque comme le week-end
  Thomas Petrachi - Vodeclic

> Formateur didactique et ouvert aux changements. Il sort des sentiers battu pour nous présenter des méthodes différentes. On se sent apte à débuter un projet après cette formation.
  Cédrik Mallet - Ministère de l'écologie
  
> Excellente formation, dans une ambiance chaleureuse. On discute, on échange, on apprend, et on repart avec plein de choses en tête qu'on a hâte d'appliquer.
  Timothée Carry - Octo  

> I asked Jean-Michel to train me as I wanted to improve my programming skills regarding RSpec and Test Driven approaches in Ruby. His workshop was rich and covered a lot of relevant topics. More importantly, it gaves us the necessary tools to pursue our own training

[Etienne Depaulis, entrepreneur](http://etiennedepaulis.com/)

> I wanted to thanks @21croissants to come to see us in Paris to give his #RailsTestingWorkshop Thanks man you did a great job ;) !

[Stéphane Gomes, taxis-g7](https://twitter.com/e_quilibre/status/279098165167284224)

## Réglement

Vous pouvez payer par virement ou je peux configurer [Weezevent](http://weezevent.com) pour la CB.

Payable d'avance et remboursable jusqu'à une semaine avant l'atelier.

## Questions?

Contactez-moi par [e-mail](mailto:jean-michel@21croissants.com) ou sur le [google group](https://groups.google.com/forum/?fromgroups#!forum/atelier-testing-rails).
