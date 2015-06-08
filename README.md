# README miniBlog #

### Piotr Krzyżanowski 215586 ###

Ruby version: 2.2.0
Ruby on Rails version: 4.2.1

* Aplikacja jest responsywna
* zaimplementowane paginacja i logowanie
* w bazie danych są przykładowe rekordy (należy użyć pliku db/seeds.rb)
* na heroku ( ) są przykładowe rekordy

### Jak odpalić lokalnie? ###

* bundle install
* bundle exec rake db:migrate
* bundle exec rake db:seed
* rails s (uruchamia lokalny serwer)


### Jak wrzucić na heroku? ###

* heroku login
* heroku create
* git add .
* git commit -m "nazwa komitu"
* git push heroku master
* heroku run rake db:migrate
* heroku run rake db:seed

### Bazowałem na: ###
https://www.railstutorial.org/book

### Przykładowy admin ###

* Email: admin@example.pl
* Password: admin123

