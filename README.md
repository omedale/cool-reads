### Set up
- npm install
- npm start

#### Install SQLite browser.
https://github.com/sqlitebrowser/sqlitebrowser

### Queries
```
query {
 books {
    id
    title
    cover_image_url
    author {
      first_name
      last_name
    }
  }
}
```
```
query {
   books {
    id
  }
}
```

```
  query {
   author (id: 1){
    id
  }
}
```
