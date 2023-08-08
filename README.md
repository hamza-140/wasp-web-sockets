# Using Websockets in Wasp

This is an example Websockets app built with Wasp.

It includes auth and a voting system.

## Running the app

```bash
cd websockets-wasp
```

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
