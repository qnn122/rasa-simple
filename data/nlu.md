## intent:greet
- hey
- hello
- hi
- good morning
- good evening
- hey there

## intent:goodbye
- bye
- goodbye
- see you around
- see you later

## intent:affirm
- yes
- indeed
- of course
- that sounds good
- correct

## intent:deny
- no
- never
- I don't think so
- don't like that
- no way
- not really

## intent:mood_great
- perfect
- very good
- great
- amazing
- wonderful
- I am feeling very good
- I am great
- I'm good

## intent:mood_unhappy
- sad
- very sad
- unhappy
- bad
- very bad
- awful
- terrible
- not very good
- extremely sad
- so sad

## intent:ask_indentity
- who are you
- what is your name
- how should i address you
- may i know your name
- are you a bot

## intent:ask_shop_open
- does the shop open on [monday] (weekday)
- does the shop open on [wednesday](weekday)
- does the shop open on [friday](weekday)

## intent:inform_country_of_origin
- i am from [malaysia](countries)
- i am from [vietnam](countries)
- i came from [thailand](countries)

## intent:ask_eaten
- what did you have for [breakfast](meal)
- what did you have for [break fast](meal:breakfast)
- what did you have for [breakfat](meal:breakfast)

## synonym:breakfast
- brekfast
- brokefast

## intent:inform_zipcode
- my zipcode is [12345](zipcode)
- my zipcode is [33456](zipcode)
- my zipcode is [94056](zipcode)

## regex:zipcode
- [0-9]{5}

## lookup:weekday
- monday
- tuesday
- wednesday
- thursday
- friday

## lookup: countries
./data/countries.txt


