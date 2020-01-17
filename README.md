# Client:HTML_vanilla_socketio <> Server:heroku_express_apollo_socketio <> DB:atlas_mongo

<img src="https://user-images.githubusercontent.com/25323947/72561042-48fc1d80-3876-11ea-8217-3b733d8d3876.png">

Dinamica del request:
Client:HTML_vanilla_socketio send mutation with fetch post or socket io event > ... (((• Server:heroku_express_apollo_socketio <> DB:atlas_mongo ))) ... > Client:HTML_vanilla_socketio

1. Fetch mutation in client javascript vanilla source: https://blog.apollographql.com/4-simple-ways-to-call-a-graphql-api-a6807bcdb355

2. Socket io cross domain source: http://maxprog.net.pl/node-js/socket-io-and-cross-domain-communication/

3. Apollo express for heroku: https://github.com/null-point-sys/express-apollo-graphql-starter desplegado en https://zen-it.herokuapp.com/graphiql

4. Authentication JWT.


