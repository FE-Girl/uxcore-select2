# uxcore-select
---

- tags: uxcore, select
- description: uxcore select
- maintainers: vincent.bian
- version: 0.1.0
- lastupdate: 2015/7/12
- screenshots:

## TL;DR

#### setup develop environment

```sh
$ git clone https://github.com/uxcore/select
$ cd select
$ npm install
$ npm run dev
```
nav http://localhost:9090/webpack-dev-server/example/ to see the demo

#### deploy to gh-pages
[refer to]( http://stackoverflow.com/questions/17643381/how-to-upload-my-angularjs-static-site-to-github-pages)
```sh
$ npm run build
$ git add build & git commit -m 'update deploy files'
$ npm run deploy
```

## Usage

```js
var Pagination = require('select');
React.render(
	<Pagination onChange={onChange} total={50} />, document.getElementById('target'));
```

### demo
http://uxcore.github.io/select/

## API

### props

|参数|说明|类型|默认值|
|---|----|---|------|