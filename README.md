#Testing Rails Workshop

##Détails
###Pour qui?

Développeur ruby, qui habite pas trop loin de Lyon et qui débute dans l'écriture de tests.

Selon le succès du premier atelier et vos attentes, il y aura d'autres ateliers, plus avancés et sur Paris également.

###Combien ça coûte?
125€ pour la matinée.

###Quand?
Lundi 28 Mai 2012 de 8h45h à 13h.

###Quel format de workshop?

* Entre 4 et 6 participants
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

L'espace de coworking ["la cordée" Charpennes](http://www.la-cordee.net/l-espace/acces-detail-espace-charpennes) à Lyon.

##Agenda

* 8h45  : Intro + petit dej offert
* 9h00  : Début de l'atelier
* 11h00 - 11h15 : Pause
* 12h00 : Questions / Réponses
* 13h00 : Fin de l'atelier. Rétrospective et déjeuner à la cordée.

### Sujets

Chaque sujet sera introduit par 1 ou 2 slides, suivi de mains dans le camboui du code.

* Bootstrap (~ 15 min)
* Framework de Tests [RSpec](https://www.relishapp.com/rspec) (~ 30 min)
  * Qualitées d’un bon Test Unitaire
  * Hooks
  * equal matcher VS eql VS ==
  * raise_error matcher
  * Sucre syntaxique
* Boite à outils (~ 20 min)
  * Speeder l'éxécution de tests avec [Spork](https://github.com/sporkrb/spork) (~ 10 min)
  * Automatiser l'éxécution de tests avec [Guard](https://github.com/guard/guard) (~ 5 min)
  * Vérifier la couverture de tests avec [SimpleCov](https://github.com/colszowka/simplecov) (~ 5 min)
* Test des libs (~ 15 min)
* Tests des Modèles (~ 45 min)
  * use_transactional_fixtures
  * Tests Data Builders avec [FactoryGirl](https://github.com/thoughtbot/factory_girl) (~ 15 min)
  * Garder une DB de tests "clean" avec [DatabaseCleaner](https://github.com/bmabey/database_cleaner) (~ 10 min)
  * Speeder les tests avec rspec-set de pcreux
  * Tests des named scope / finders (~ 15 min)
* Tests d'intégration avec [capybara](https://github.com/jnicklas/capybara) (~ 45 min)
  * Pages sans js avec le driver rack_test (~ 30 min)
  * Ajax avec le driver [webkit](https://github.com/thoughtbot/capybara-webkit) (~ 15 min)
  * Debug capybara
* Mocks objects avec [rspec-mock](https://www.relishapp.com/rspec/rspec-mocks/docs) (~ 15 min)
  * Introduction Mocks - Stubs - Test Doubles
  * Exemple de stubs: GeoLocalization
  * stubs: Time & DateTime
  * FactoryGirl build_stubbed
  * Mocks

Bonus, s'il reste du temps:

* Tests des Mailers avec [email_spec](https://github.com/bmabey/email-spec) (~ 15 min)
* Tests des routes (~ 10 min)
* Tests des [Controlleurs](http://solnic.eu/2012/02/02/yes-you-should-write-controller-tests.html) (~ 15 min)
* Test des Helpers (~ 15 min)

##Inscription

Merci de t'inscrire en répondant à ce [sondage de 5 minutes](http://www.21croissants.com/tdd).

## Réglement

Vous pouvez payer les 125€ en liquide / cheque / virement ou je peux configurer [Weezevent](http://weezevent.com) pour la CB.
Je suis auto-entrepreneur, je ne facture pas la TVA mais je peux vous faire une facture si besoin.

Payable d'avance et remboursable jusqu'à une semaine avant l'atelier.

##Questions?

Contactez-moi par [e-mail](http://www.workingwithrails.com/person/6331-jean-michel-garnier/enquire/new) ou sur le [google group](https://groups.google.com/forum/?fromgroups#!forum/atelier-testing-rails).
