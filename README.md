Swiss Twitter Accounts
======================

List of Twitter accounts from Switzerland divided by category, in JSON format. The goal is to gather the accounts that are influent and potentially followed only in Switzerland.

Lists available:
- newspapers
- politicians
- radios
- televisions
- sports-teams
- political-parties
- personalities

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
- poilitical parties
- events
- ...

Contribute
----------

If you want to add accounts, feel free to send a PR!
Please verify that your JSON files are valid before pushing. You can use jsonlint (`npm install jsonlint -g`) then verify the files with the `jsonlint` command.
