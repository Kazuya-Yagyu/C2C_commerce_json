# Deploy `json-server` to `{{ free hosting site }}`

> Instructions how to deploy the full fake REST API [json-server](https://github.com/typicode/json-server) to various free hosting sites. Should only be used in development purpose but can act as a simpler database for smaller applications.

- [**Create your database**](#create-your-database)
- [Deploy to **Heroku**](#deploy-to-heroku)

## Create your database

1. Press the green `Use this template`-button in the right corner
2. Give your new repo a name and press the green `Create repository from template`-button
3. Clone your newly created repository to your computer

4 . Change the contents of `db.json` to **your own content** according to the [`json-server example`](https://github.com/typicode/json-server#example) and then `commit` your changes to git locally.

_this example will create `/posts` route , each resource will have `id`, `title` and `content`. `id` will auto increment!_

```json
{
  "posts": [
    {
      "id": 0,
      "title": "First post!",
      "content": "My first content!"
    }
  ]
}
```
