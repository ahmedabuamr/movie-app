

## Development

From your terminal:

after install code on your PC :
run:
```sh
npm install
```
 to start run app
```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `remix build`

- `build/`
- `public/build/`

## API for Search Movies and show list movies
I used api from themoviedb website to integrate api 
link the website: https://www.themoviedb.org/

## Framework for UI
I used Tailwind Css for UI design