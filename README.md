**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/AntonioErdeljac/next13-airbnb-clone.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_SECRET=
```
### Get env data
1. database url. access mongo atlas connect mongo for vscode to get url, then browser collections to work normally
2. nextauth just let 'NEXTAUTH_SECRET'
3. github id secret get from github, setting, developer setting, OAth create new app
4. setup cloudinary. create account -> set cloud name, set uploadpreset in imageUpload in setting 


### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |
