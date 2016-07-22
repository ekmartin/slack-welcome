# slack-welcome

> Sends a welcome message to new Slack users.

## Installation and usage
Install with npm:
```bash
$ npm install -g slack-welcome
$ SLACK_TOKEN="token" WELCOME_MESSAGE="hello" slack-welcome
```

or by cloning the repository:

```bash
$ git clone https://github.com/ekmartin/slack-welcome.git && cd slack-welcome
$ npm install
$ SLACK_TOKEN="token" WELCOME_MESSAGE="hello" npm start
```

## Configuration
slack-welcome requires two environment variables:

* `SLACK_TOKEN`: A bot user token, can be created [here](https://my.slack.com/services/new/bot).
* `WELCOME_MESSAGE`: The message that should be posted to new users.

### Tests
Run the tests with:
```bash
$ npm test
```

## License

(The MIT License)

Copyright (c) 2016 Martin Ek <mail@ekmartin.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
