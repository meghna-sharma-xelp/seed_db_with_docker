FROM mongo

COPY users.json /users.json
CMD mongoimport --host mongo --db Devopstest --collection users --type json --file /users.json --jsonArray
