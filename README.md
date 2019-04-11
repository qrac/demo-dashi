# Demo Dashi

## About

Web 制作・アプリモック制作用のデモデータ。UI 構築に最低限必要だった部分を書いて外部化・使いまわしているだけなので、本番データとしては不完全です。

- 都道府県 `src/area`
  - `地域 > 都道府県` を JSON データ化
  - 自作手打ち
- 路線 `src/line`
  - `都道府県 > 路線グループ > 路線 > 駅` の一部を JSON データ化
  - 参考 1：[駅データ 無料ダウンロード 『駅データ.jp』](http://www.ekidata.jp/)
  - 参考 2：[鉄道路線のラインカラー一覧とは - ニコニコ大百科](https://dic.nicovideo.jp/a/%E9%89%84%E9%81%93%E8%B7%AF%E7%B7%9A%E3%81%AE%E3%83%A9%E3%82%A4%E3%83%B3%E3%82%AB%E3%83%A9%E3%83%BC%E4%B8%80%E8%A6%A7)
  - 参考 3：[日本の鉄道ラインカラー一覧 - Wikipedia](https://ja.wikipedia.org/wiki/%E6%97%A5%E6%9C%AC%E3%81%AE%E9%89%84%E9%81%93%E3%83%A9%E3%82%A4%E3%83%B3%E3%82%AB%E3%83%A9%E3%83%BC%E4%B8%80%E8%A6%A7)

## Use

### [npm](https://www.npmjs.com/package/demo-dashi)

```bash
$ npm install demo-dashi
```

## CDN (API)

### [jsDelivr](https://www.jsdelivr.com/package/npm/demo-dashi)

```
https://cdn.jsdelivr.net/npm/demo-dashi@0.0.2/src/area/japan.json
https://cdn.jsdelivr.net/npm/demo-dashi@0.0.2/src/line/japan.json
```

## License

- CC0 1.0 Public Domain

## Credit

- Author: [Qrac](https://qrac.jp)
- Organization: [QRANOKO](https://qranoko.jp)
