# PayTrack

給料・シフト・扶養・目標を管理するスマホ向けWebアプリの初期版です。

## iPadだけでSafariから使う最短手順

1. GitHubで新しいリポジトリ `paytrack` を作る
2. このZIPを展開し、中身をリポジトリへアップロード
3. Vercelにログインし、GitHubの `paytrack` をImport
4. Deployを押す
5. 発行されたURLをSafariで開く
6. Safariの共有ボタン →「ホーム画面に追加」

## PCがある場合

```bash
npm install
npm run dev
```

`http://localhost:3000` を開いてください。

## 現在できること

- シフト追加・編集・削除
- 深夜手当・休憩・交通費を含む給与計算
- 年収・扶養残額・次回給与見込み
- カレンダー
- 目標登録・優先目標
- お知らせ
- お問い合わせ画面（現状はデモ送信）
- Safariのローカルストレージへの保存
- ホーム画面追加用manifest

## 次の実装

Supabase認証・クラウド保存・実際のお問い合わせ送信・利用規約・プライバシーポリシー。
