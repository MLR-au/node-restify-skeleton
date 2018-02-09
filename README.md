# API Gateway

The API border router.

## To setup

```
> yarn install
```

## To develop just run:

```
> yarn develop
```

This will start up the API processing watching for changes in addition to watchers
on spec files in the `src` and `e2e` folders; intelligently watching for changes
and reloading the respective component as required.

## Tests

This repo comes setup with `mocha` as the test runner and `chai` for assertions.
It also has `chakram` included for BDD style testing.
