#### https://stackoverflow.com/questions/50682080/is-it-possible-to-lookup-a-database-in-a-dialogflow-intent
#### Is it possible to lookup a database in a Dialogflow intent?

#### EXCERPT

##### You can't access a database from Dialogflow directly, but you can build your own fulfillment backend that can do anything you want. It communicates with Dialogflow via HTTP requests/responses in the Dialogflow Webhook format.
##### Here is an example fulfillment that reads data from Firebase database - https://github.com/actions-on-google/dialogflow-updates-nodejs
