# FileTree

```
./
  |- src/
    |- assets/
    |- components/
    |- pages/
    |- router/
    |- store/
    |- App.vue
    |- main.js
```
# Assets

css image svg など

# Components

ページ内で使う部品を管理するフォルダです。ヘッダーやフッター、サイドバーやもっと細かくボタンコンポーネントなどがあっても問題ないです。ただし、使わないコンポーネントになってしまった場合は確認をとって削除させていただきます

# Pages

アプリケーションのページです。Conponentsフォルダ内の部品の寄せ集めで作れるのがベストですが、直にhtmlを書いても問題はないです。

# Rotuer

ルーティングを設定するファイルを管理します。

# Store

Vuex Storeを管理します。mutations actions などが肥大化する場合はむモジュール分割しながら管理します。
