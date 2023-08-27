# nosql-challeng
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

Code used to import establishments.json from the resource folder:
mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json
