# instagram-scraper

ES6, Fetch, Promise, JSON version forked from this nice repo:

https://github.com/rarcega/instagram-scraper-node

## INSTALL
```sh
npm i --save https://github.com/timothyerwin/instagram-scraper.git
```

## USAGE

```javascript
  import instagram from 'instagram-scraper';

  instagram('someuser').media().then((results) => {
    console.log(results);
  });
```

## RESULTS
Results will basically be what you get from this URL:

https://www.instagram.com/:user/media/
