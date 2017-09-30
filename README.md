# The Async Force Ep 4

Async Exercise using Server side XHR accessing the swapi


## Excercise
*Remember to commit after each step.*

1. Inspect the the swapi data
    - https://swapi.co/api/starships/2/
    - https://swapi.co/api/starships/3/
    - https://swapi.co/api/starships/5/
    - https://swapi.co/api/starships/9/
1. edit the `app.js`.
1. fetch the json data from swapi to save starships into `data/[starship_]n.json`
    - use the fs module (async only, no sync functions)
    - https://swapi.co/api/starships/2/ -> `data/starship_2.json`
    - https://swapi.co/api/starships/3/ -> `data/starship_3.json`
    - https://swapi.co/api/starships/5/ -> `data/starship_5.json`
    - https://swapi.co/api/starships/9/ -> `data/starship_9.json`
1. read from all `4` json files in `data/` (individually) using `fs.createReadStream`, parse the contents as json
1. extract the `cost_in_credits` values of each starship
1. print out the total cost in credits of all `4` starships to standard output
