# Remix with React 19

following this guide https://react.dev/blog/2024/04/25/react-19-upgrade-guide

You can also check out this branch where I was playing with the hydration errors in React 19:

- https://github.com/JLarky/remix-react-19-template/commits/hydration-errors-demo/

## Development

Run the Vite dev server:

```shellscript
bun dev
```

## Deployment

First, build your app for production:

```sh
bun run build
```

Then run the app in production mode:

```sh
bun start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying Node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `bun build`

- `build/server`
- `build/client`
