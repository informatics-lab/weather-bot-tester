Weather Bot Tester
==================

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
