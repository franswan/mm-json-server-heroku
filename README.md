# M3me Magic JSON Server

JSON based database to deploy to Heroku for developer access to the card library API: https://meme-magic-json-server-heroku.herokuapp.com/

Card library is maintained in the meme-magic repo: https://github.com/franswan/meme-magic
- n3wbs can add cards via Foresty
- nerds can pull request the meme-magic repo


## Update the JSON Server

To import current card information from meme-magic card library:

`npm run update-db`

Send it to Heroku

`git add .`
`git commit -m "updating the cards again dawg"`
`git push heroku main:master`

Card API will now be updated so any client apps will have access to fresh cards and updated values

https://meme-magic-json-server-heroku.herokuapp.com/
