# put_to_bed

## Uppgiftsbeskrivning ##

Världen har tagits över av robotar. 

De behöver din hjälp med att skapa en funktion de kan använda för att natta all världens barn.

Skapa en funktion `put_to_bed` som tar ett namn (`name:`) **som argument** och **returnerar** "*Nighty Nighty, {namnet}!*"

### Flödesschema ###

Innan du börjar koda ska du skapa ett flödesschema för programmet. 

Testa flödesschemat med penna och papper.

### Exempel ###

```ruby
   
	puts put_to_bed(name: 'Billy-Bob')
    #=> 'Nighty nighty, Billy-Bob!'
```

### Tester ###

Testerna finns i `test/test_put_to_bed.rb`

Kör testerna (från uppgiftens rotmapp): `ruby test/test_put_to_bed.rb`


### Bonusbana ###

Vad händer om man skickar in en tom `String` som argument?

Uppdatera programmet så det hanterar felaktig input.

### Länkar ###

* [Exercise 19: Functions and Variables](http://learnrubythehardway.org/book/ex19.html)
* [Exercise 21: Functions Can Return Something](http://learnrubythehardway.org/book/ex21.html)
* [Ruby 2 Keyword Arguments](https://robots.thoughtbot.com/ruby-2-keyword-arguments)
