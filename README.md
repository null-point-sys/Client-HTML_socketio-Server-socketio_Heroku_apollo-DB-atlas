# Client/HTML_socketio-Server/socketio_Heroku_apollo-DB/atlas

<img src="https://user-images.githubusercontent.com/25323947/72561042-48fc1d80-3876-11ea-8217-3b733d8d3876.png">

Client_HTML_socketio send mutation from html fetch post or socket io event > ... (((• socketio_Heroku_apollo_server <> DB Atlas ))) ... < Client_HTML_socketio

Fetch mutation in client javascript vanilla:

fetch('https://1jzxrj179.lp.gql.zone/graphql', {
  method: 'POST',
  headers: { 'Content-Type': 'application/json' },
  body: JSON.stringify({ query: '{ posts { title } }' }),
})
  .then(res => res.json())
  .then(res => console.log(res.data));
  
  source: https://blog.apollographql.com/4-simple-ways-to-call-a-graphql-api-a6807bcdb355


