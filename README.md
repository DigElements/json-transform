# json-transform

An element used to perform one or more transformations on JSON.  Useful when you 
need to munge the results of an AJAX request.

## Install

* bower install --save DigElements/json-transform
* add a line to import the html file like this:

`<link rel="import" href="../bower_components/json-transform/json-transform.html">`

## Testing

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.
