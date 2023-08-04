# Using Websockets in Wasp

This is an example Websockets app built with Wasp.

It includes auth and a voting system.

## Running the app

```bash
cd websockets-wasp
```

```bash
wasp db migrate-dev
```

start the app! (this also installs all dependencies)

```bash
wasp start
```

Check out the `src/server/websocket.ts` and `src/client/pages/MainPage.tsx` to see how Websockets are used in Wasp.
