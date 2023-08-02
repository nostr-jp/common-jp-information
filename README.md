# Common JP Information [Open Data]

このリポジトリでは、開発者向けに日本語の公開情報を掲載しています。

## Resources

すべての情報をJSONで公開しています。アプリケーション等から取得して使用することが可能です。

### relays.json

日本語リレーの一覧です

```json
[
    {
        "key": "string (一意のID)",
        "name": "string (リレー通称名)",
        "name_river": "string (川の名前)",
        "target": "[\"JP\"] array",
        "allow": "[\"JP\"] array",
        "deny": "[\"GLOBAL\"] array",
        "description": "string (リレーの説明など)",
        "url": "string (wss://your-relay.domain)",
    }
]
```
