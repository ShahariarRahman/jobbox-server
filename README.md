# jobbox-server

## vercel deploy

### [Installing Vercel CLI](https://vercel.com/docs/cli#installing-vercel-cli)

- `npm i -g vercel`

### [Checking the version](https://vercel.com/docs/cli#checking-the-version)

- `vercel --version`

### [vercel.json](https://github.com/ShahariarRahman/jobbox-server/commit/5d1958f586a217561e52c3faeac23bfa4b493b45)

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

### [login](https://vercel.com/docs/cli/login)

- `vercel login`

### deploy cli :

```
$ vercel deploy
$ Set up and deploy "location..."? [Y/n] y
$ Which scope do you want to deploy to? select an account
$ Link to existing project? [y/n] n
$ What is your project's name? (default-name) or type name
$ In which directory is your code located? ./
```

### update vercel deploy

- ` vercel deploy`
- after each update new server generated
- - delete previous unnecessary server

### Environment variables in vercel

```
> go to [dashboard](https://vercel.com/dashboard)
> select project
> go to settings
> go to Environment Variables
> check Production, Preview, Development
> fill-up environment variable
```
