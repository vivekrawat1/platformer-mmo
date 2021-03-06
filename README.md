# Platformer MMO

This game will have 3 different maps to join. Each map has a player limit of 10. Once the limit is reached, a new instance of that map will be created. Each instance holds his own state.

On the server side I'll use Colyseus as game server, express for http requests, MongoDB as the database and MatterJs as physics engine.

On the client side I'll use VueJs for building ui components and Phaser 3 to render the game.

Authentication will be through jsonwebtokens.

**Live demo**

- [Monitor GameServer](https://platformer-mmo.herokuapp.com/colyseus)

## Development

Open two terminals

```bash
cd server
npm install
npm run dev
```
- [Monitor Server](http://localhost:2567/colyseus)

```bash
cd client
npm install
npm run dev
```
- [Client](http://localhost:1234)

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Checklist

- ~~create express server~~
- ~~create User model with email, password, clientId, location~~
- ~~create auth routes to catch data~~
- ~~create vuejs project~~
- ~~create basic views, components and routes~~
- ~~create navbar~~
- ~~create api service~~
- ~~create register form and sent credentials to server~~
- ~~create login form and sent credentials to server~~
- ~~handle register request on the server~~
- ~~handle login request on the server~~
- ~~handle validation~~
- ~~create game server~~
- ~~create GameRoom and register it with custom options town, forest and fields~~
- ~~create game component~~
- ~~setup phaser project~~
- ~~setup client connection~~
- ~~fetch player location from the http api and join room based on location~~
- ~~setup game server authentication~~
- ~~check user location in db before joining room~~
- ~~create different game states based on map~~
- create physics engine
- create player state and physical body on the server
- create phaser sprite and setup keyboard input events
- create player animations
- setup portals to travel map
- interaction ui and canvas
- create block
- create mini map
- create enemy
- setup custom ui