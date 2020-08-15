Cicocore Library
=======

A pure and powerful JavaScript CICO library.


## Get Started

```
npm install cicocore-lib
```

```
bower install cicocore-lib
```

## Security

We're using cicocore-lib in production, but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.



## Contributing

Please send pull requests for bug fixes, code optimization, and ideas for improvement. 

## Building the Browser Bundle

To build a cicocore-lib full bundle for the browser:

```sh
gulp browser
```

This will generate files named `cicocore-lib.js` and `cicocore-lib.min.js`.

## Development & Tests

```sh
git clone https://github.com/coinicles/cicocore-lib
cd cicocore-lib
npm install
```

Run all the tests:

```sh
gulp test
```

You can also run just the Node.js tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

