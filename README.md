# Jokes RestAPI Using Nodejs

I have created an array with random jokes stored in an array, When the http standard requests you can access the joke you like too.

## API Reference End-Points

#### local host

```https
    https:localhost300
```

#### GET random Jokes

```https
  GET /random/
```

#### GET Specific Joke

```https
  GET /jokes/:id
```

#### GET a joke by filtering on a joke type

```https
  GET /filter?type="Your_Type"
```

#### POST a new Joke

```https
  POST /jokes
```

#### PUT a joke

```https
  PUT /jokes/:id
```

#### PATCH a joke

```https
  PATCH /jokes/:id
```

#### DELETE a joke

```https
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
