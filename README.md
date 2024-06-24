# Using Websockets in Wasp

This is an example Websockets app built with Wasp.

It is also a part of a tutorial, [How to build a real-time voting app with WebSockets, React, & Typescript](https://wasp-lang.dev/blog/2023/08/09/build-real-time-voting-app-websockets-react-typescript).

[![wasp websockets app](image.png)](https://www.youtube.com/watch?v=Twy-2P0Co6M)

This app also includes Wasp's integrated auth and a voting system (again, neat!).

## Running the app

_If you get stuck at any point, feel free to join our [Discord server](https://discord.gg/rzdnErX) and ask questions there. We are happy to help!_

Download and install Wasp

```bash
curl -sSL https://get.wasp-lang.dev/installer.sh | sh
```

Clone this repo...

```bash
git clone https://github.com/wasp-lang/websockets-example-app.git
```

....and navigate to the project directory

```bash
cd websockets-example-app
```

make sure you have [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed and start the DB

```bash
wasp start db
```

start the app! (this also installs all dependencies)

```bash
wasp start
```

Check out the `src/server/websocket.ts` and `src/client/pages/MainPage.tsx` to see how Websockets are used in Wasp.

## Need Help?

Wasp Docs: https://wasp-lang.dev/docs

Feel free to join our [Discord server](https://discord.gg/rzdnErX) and ask questions there. We are happy to help!
