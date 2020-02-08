# Search Engine API Puppeteer

Search Engine API with Node/Express and Puppeteer using Google Search

The API scrapes Top Search Results from Google Search

[Blog Post](https://dev.to/waqasabbasi/building-a-search-engine-api-with-node-express-and-puppeteer-using-google-search-4m21)

To get started, make sure to run `npm install` to install all dependencies
```
npm install
```

To start the server:
```
npm start
```

You can send a `GET` request with your search query:
```
http://localhost:3000/search?searchquery=cats
```

Example Response
```
[
  {
    title: 'Cats Are Funny',
    description: 'Watch funny videos about cats`,
    url: 'catsarefunny.com'
  },
  {
      title: 'Cats Are Cute',
      description: 'Watch cute videos about cats`,
      url: 'catsarecute.com'
    },
]
```
