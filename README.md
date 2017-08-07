Weather Bot Tester
==================

A tool for testing [Bot Framework](https://dev.botframework.com/) bots using [Direct Line](https://docs.microsoft.com/en-us/bot-framework/rest-api/bot-framework-rest-direct-line-3-0-concepts).

```shell
cat <<'EOF' >>/tmp/bot-tests.json
[
  ["Hi",
   "Jacob",
   "What's the wether in exeter?"]
]
EOF

export DIRECT_LINE_SECRET=aabbccddee
export BOT_TESTS_FILE=/tmp/bot-tests.json

npm install
npm start
```
