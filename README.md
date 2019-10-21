Swiss Twitter Accounts
======================

List of Twitter accounts from Switzerland divided by category, in JSON format. The goal is to gather the accounts that are influent and potentially followed only in Switzerland.

Lists available:
- banks
- companies
- events
- insurances
- newspapers
- personalities
- political-parties
- politicians (--> https://parl.ch/tweets)
- radios
- sports-teams
- telcos
- televisions
- transportations

Format:
```
{
	"accounts": [
		{
			"screen_name": "jackycasas_",
			"name": "Jacky Casas",
			"langs": ["EN", "FR"]
		},
		{
			...
		}
	]
}
```

The following fields can be added to the structure:
- "city": if the account is linked to only one city (eg. "Lausanne", "Bern", "Thun", "Lugano")
- "region": if the account is specific to a region or canton (eg. "Romandie", "Bern", "Valais")

Ideas for new lists:
- cities
- institutions
- events (music festivals, expos)


Contribute
----------

If you want to add accounts, feel free to send a PR!
Please verify that your JSON files are valid before pushing. You can use jsonlint (`npm install jsonlint -g`) then verify the files with the `jsonlint` command.


Notes
-----

Regarding the file `politicians.json`: all the members of the national council with a Twitter account are listed (updated with the new council of 2019). Here are the councelors without a Twitter account:

- Page Pierre-André
- Wobmann Walter
- Eymann Christoph
- Zuberbühler David
- Ritter Markus
- Büchel Roland Rino
- Martullo-Blocher Magdalena
- Feller Olivier
- Maillard Pierre-Yves
- Crottaz Brigitte
- Nicolet Jacques
- Brélaz Daniel
- Ruppen Franz
- de la Reussille Denis
- Mazzone Lisa
- Gschwind Jean-Paul
- Fridez Pierre-Alain
- Walti Beat
- Matter Thomas
- Rutz Gregor
- Walliser Bruno
- Aebi Andreas
- Geissbühler Andrea
- Pieren Nadja
- Rösti Albert
- von Siebenthal Erich
- Vitali Albert
- Müller Leo
- Birrer-Heimo Prisca
- Gmür Alois
- Dettling Marcel
- Schwander Pirmin
- Keller Peter
- Bourgeois Jacques
- Gafner Andreas
- Stadler Simon
- Weichelt-Picard Manuela
- Herzog Eva
- Rechsteiner Thomas
- Vincenz-Stauffacher Susanne
- Friedli Esther
- Brunner Thomas
- Giacometti Anna
- Locher Benguerel Sandra
- Gallati Jean-Pierre
- Giezendanner Benjamin
- Strupler Manuel
- Farinelli Alex
- de Quattro Jacqueline
- Kamerzin Sidney
- Clivaz Christophe
- Maitre Vincent
- Dandrès Christian
- Matter Michel
- Haller Jocelyne
- Walder Nicolas