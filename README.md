#Testing Rails Workshop

##Détails
###Pour qui?

Développeur ruby, qui habite pas trop loin de Paris et qui débute dans l'écriture de tests.

###Combien ça coûte?
250€ pour la journée..

###Quand?
La prochaine session aura lieu en juin ou pendant l'été 2012.

###Quel format de workshop?

* Entre 6 et 10 participants
* une matinée de 4h avec ptit dej et pause café
* Ecriture de tests avec [RSpec](https://www.relishapp.com/rspec)
* Nous construirons le programme détaillé ensemble, je vous contacterai sur skype pour connaitre vos attentes

###Que préparer?

Son ordinateur portable (linux ou mac) avec [ruby set up](http://installfest.railsbridge.org/installfest/installfest)

Clone le repo :

`git clone git://github.com/21croissants/testing-rails-workshop.git && cd testing-rails-workshop`

Execute le script de bootstrap pour installer toutes les dépendances de dev:

`script/bootstrap`

###Où?

TBD

##Agenda

* 8h45  : Intro + petit dej offert
* 9h00  : Début de l'atelier
* 11h00 - 11h15 : Pause
* 12h00 : Questions / Réponses
* 13h00 : Déjeuner
* 14h30 : Reprise de l'atelier
* 17h30 : Rétrospective

### Sujets

Chaque sujet sera introduit par 1 ou 2 slides, suivi de mains dans le camboui du code.

* Bootstrap
* Framework de Tests [RSpec](https://www.relishapp.com/rspec)
  * Qualitées d’un bon Test Unitaire
  * Hooks
  * equal matcher VS eql VS ==
  * raise_error matcher
  * Sucre syntaxique
* Boite à outils
  * Speeder l'éxécution de tests avec [Spork](https://github.com/sporkrb/spork) 
  * Automatiser l'éxécution de tests avec [Guard](https://github.com/guard/guard)
  * Vérifier la couverture de tests avec [SimpleCov](https://github.com/colszowka/simplecov)
* Test des libs
* Tests des Modèles
  * use_transactional_fixtures
  * Tests Data Builders avec [FactoryGirl](https://github.com/thoughtbot/factory_girl) 
  * Garder une DB de tests "clean" avec [DatabaseCleaner](https://github.com/bmabey/database_cleaner)
  * Speeder les tests avec rspec-set de pcreux
  * Tests des named scope / finders
* Tests d'intégration avec [capybara](https://github.com/jnicklas/capybara)
  * Pages sans js avec le driver rack_test
  * Ajax avec le driver [webkit](https://github.com/thoughtbot/capybara-webkit)
  * Debug capybara
* Mocks objects avec [rspec-mock](https://www.relishapp.com/rspec/rspec-mocks/docs)
  * Introduction Mocks - Stubs - Test Doubles
  * Exemple de stubs: GeoLocalization
  * stubs: Time & DateTime
  * FactoryGirl build_stubbed
  * Mocks
* Tests des Mailers avec [email_spec](https://github.com/bmabey/email-spec) 
* Tests des routes
* Tests des [Controlleurs](http://solnic.eu/2012/02/02/yes-you-should-write-controller-tests.html)
* Test des Helpers

##Inscription

Merci de t'inscrire en répondant à ce [sondage de 5 minutes](http://www.21croissants.com/tdd).

## Réglement

Vous pouvez payer en liquide / cheque / virement ou je peux configurer [Weezevent](http://weezevent.com) pour la CB.
Je suis auto-entrepreneur, je ne facture pas la TVA mais je peux vous faire une facture si besoin.

Payable d'avance et remboursable jusqu'à une semaine avant l'atelier.

##Questions?

Contactez-moi par [e-mail](http://www.workingwithrails.com/person/6331-jean-michel-garnier/enquire/new) ou sur le [google group](https://groups.google.com/forum/?fromgroups#!forum/atelier-testing-rails).
