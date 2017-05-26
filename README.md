# _Github User_

### _26 May 2017_

#### By Najib Osman:

## Description:
_Github User_ is a simple interface interacting with the Github API

## Goal:
Reflect an introduction to advanced Javascript, interacting with APIs and JSON

### Technologies Used:
- html
- javascript
- css
- gulp
- json
- bower

### Usage:

You will need to generate an API key through Github:

 -  Settings -> Personal access tokens -> Genrate new token

Do *not* grant any permissions on the tokens

```
git clone https://github.com/najibosman/githubuser.git
cd githubuser
npm install
bower install
```

You will need to create a .env file in the project's root directory and configure your
api key like:

```
exports.apiKey = '{your github api key here}'
```

For Development:
```
gulp build
```

For Production:
```
gulp build --production
```
The key difference is production files are minified.

### License:
#### The MIT License (MIT)
Copyright (c) 2016 Najib Osman

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
