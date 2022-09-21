## Single-SPA error by CORS

#### To reproduce this error

1. `npx create-single-spa`

2. Pass these settings

```bash
? Directory for new project - react-spa
? Select type to generate - single-spa application / parcel
? Which framework do you want to use? react
? Which package manager do you want to use? npm
? Will this project use Typescript? No
? Organization name (can use letters, numbers, dash or underscore) - andres
? Project name (can use letters, numbers, dash or underscore) - react-spa

```

5. `cd /react-spa`

6. `npm install`

7. `npm start -- --port 8500`

8. In your browser open this link: `http://single-spa-playground.org/playground/instant-test?name=@andres/react-spa&url=8500`
