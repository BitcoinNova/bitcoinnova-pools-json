# bitcoinnova-pools-list

The goal of this repository is to have a central list of pools for Bitcoin Nova (https://bitcoinnova.org) mining. If you run a pool, please submit a Pull Request against *v2/bitcoinnova-pools.json* to get added.

This list can be consumed in your application so you'll always have an up-to-date list of pools. To consume the list, just use the following URL: https://raw.githubusercontent.com/BitcoinNova/bitcoinnova-pools-json/master/v2/bitcoinnova-pools.json

## Contributing

Please add your pool to the list in **alphabetical order**, named using CamelCase.domain style, and **including trailing slashes** for the `url` and `api` values.

**e.g.**
```
    {
        "name" : "MyPool.com",
        "url" : "https://btn.mypool.com/",
        "api" : "https://btn.mypool.com/api/",
        "type" : "forknote"
    },
```

### Possible values for 'type'
 - forknote
 - forknote-alt
 - node.js
 - other
