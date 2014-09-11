# webapp-allspark

![allspark](http://i.imgur.com/VI4mdtp.jpg?1)

The All Spark as seen on the Transfomers movies


# About

webapp-allspark is our Web-app Start-kit for generating a pure frontend project.

## key setting
1. coffee script
2. reactjs
3. browserify (*multiple entries, most reference is single entry*)
4. compass

# Install

```shell
npm i && bower i && bundle install
```

# How to run it?

```shell
gulp server
```
and open browser <http://localhost:3000>

# Test 

You can add test script at here: [/test/spec](https://github.com/blackbing/webapp-allspark/tree/develop/test/spec)

```shell
gulp test
```

# Build project

```shell
gulp build
```

# Build project as production

```shell
NODE_ENV=production gulp build
```
