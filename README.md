# Jokes RestAPI Using Nodejs

I have created an array with random jokes stored in a array,When the http standard request you can access the joke you like too.

## API Reference End-Points

#### local host

```http
    http:localhost300
```

#### GET random Jokes

```http
  GET /random/
```

#### GET Specific Joke

```http
  GET /jokes/:id
```

#### GET a joke by filtering on a joke type

```http
  GET /filter?type="Your_Type"
```

#### POST a new Joke

```http
  POST /jokes
```

#### PUT a joke

```http
  PUT /jokes/:id
```

#### PATCH a joke

```http
  PATCH /jokes/:id
```

#### DELETE a joke

```http
  DELETE:  /jokes/:id
           /all
```

## PARAMETER

```javascript
const jokes = {
  id: INT,
  jokeText: STRING,
  jokeType: STRING,
};
```

## Joke Type Reference

| Type     |
| -------- |
| Wordplay |
| Puns     |
| Science  |
| Movies   |
| Food     |
| Math     |
| Sports   |

# SUPPORT

For support please contact me on [Gmail](kzajjaj@gmail.com) or visit my [Github](https://github.com/Zajjaj-Khan) page, Feel free to update this repository , Would glad if someone uses it in their projects.
_PEACE_ ✌️
