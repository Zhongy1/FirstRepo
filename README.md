## Webserver example

Minimalistic webserver as an introductory concept of what is a server.

## Instructions

Clone this repo and navigate into it, then install packages

```bash
npm install
```
This command uses the "dependencies" specified in package.json to download your packages

To run, use ts-node. Ts-node is used to run typescript files
```bash
npx ts-node server
```

npx is an npm package runner, if you don't have the command, install it globally so you can use it whenever
```bash
npm install -g npx
```

See if your server is running properly. Open up a browser and go to "localhost:8000".

To see websocket working on chrome, right click the window and click inspect. On the console tab, you should be able to see a message sent by the server.