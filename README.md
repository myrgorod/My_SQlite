# my-sqlite

## Task

Hello, my friend!

That project realizes  requests to CSV database .

## Description
In the first part we create "my_sqlite_request" 
that will has a similar behavior like a request on the real sqlite. 

## Installation

For simple checking that project  be use requests in the my_sqlite_request.rb
 removing the comments symbols  before them.

## Usage

The second part is programm, which will be work with the Command Line Interface (CLI) 
It will use readline and we will run it with ruby my_sqlite_cli.rb.

The checking of code need to make use the command line.
Please, put the command into command line.:
ruby my_sqlite_cli.rb

Question 6 of 10

SELECT * FROM nba_player_data.csv

Question 7 of 10

SELECT name, position FROM nba_player_data.csv WHERE name = 'Zaid Abdul-Aziz'

Question 8 of 10

INSERT INTO nba_player_data.csv VALUES ('Mick Jagger','1967','2100','F', '5-9', '200','June 26, 1943','Dartford Grammar School')

Question 9 of 10

UPDATE nba_player_data.csv SET height='20',weight='500'WHERE name ='Mick Jagger'

Question 10 of 10

DELETE FROM nba_player_data.csv WHERE name = 'Mick Jagger'

### The Core Team
Stupakova Oksana
Markov Mykola
