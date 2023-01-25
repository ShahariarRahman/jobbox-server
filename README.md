# jobbox-server

## vercel deploy

### [Installing Vercel CLI](https://vercel.com/docs/cli#installing-vercel-cli) :

- npm i -g vercel

### [Checking the version](https://vercel.com/docs/cli#checking-the-version)

- vercel --version

### vercel.json

- version | builds | routes

```
{
  "version": 2,
  "builds": [
    {
      "src": "./index.js",
      "use": "@vercel/node"
    }
  ],
  "routes": [
    {
      "src": "/(.*)",
      "dest": "/"
    }
  ]
}
```
