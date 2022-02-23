# vue-and-asynJS-exam

Two exercices of JS to make a single game of avatars grabbing points:
* First one is coded with JS using asing functions as **fetch** with a JSON API Server.
* Second one is done with Vue Framework via CDN usage


## Exercise 1 - Running the JSON API Server

Install JSON Server

```
npm install -g json-server
```

Use `db.json` file with some data

```json
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```

Start JSON Server

```bash
json-server --watch db.json
```

Now if you go to [http://localhost:3000/avatars](http://localhost:3000/posts/1), you'll get the previous json data.


## Exercise 2 - Vue 3 CDN

Make sure CDN is loaded via script at head:

```
<script src="https://unpkg.com/vue@next"></script>
```

Open __index-2.html__ file at browser.


