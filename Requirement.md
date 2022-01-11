# Requirement Disscussion

## アカウント登録
- user?(仮名)
    - name
    - email
    - password
- user?(ログイン済み)のみが使用できる機能
    - ?

## ゲスト機能
- guest?(仮名)
    - ?

## 保存機能
- ギャラリー表示,一覧表示
- [npm: localStorageDB ](https://github.com/knadh/localStorageDB)
- [konva: vue-save-load](https://konvajs.org/docs/vue/Save-Load.html#page-title)
- 調査中: [issue](https://github.com/Recursion-Group-K/sketch/issues/2)

## 描画機能
- 共通
    - マウスのポインター
    - konvaでの基本的な描画開発
    - redo,undo
    - 色変更
        - [type="color"](https://developer.mozilla.org/ja/docs/Web/HTML/Element/input/color)
        - [styleの例: shelace](https://shoelace.style/components/color-picker)
        - [stack overflow](https://stackoverflow.com/questions/47971289/input-type-color-styling/47971607)
    - 太さ変更(変更可能)
        - min 1px
        - max 200px
- Eatch a Sketch
    - タッチorクリックで描画位置の変更
    - Eatch a Sketchの描画方法開発(webでの操作法について相談予定)
    - [スマホのアイデア](https://whimsical.com/KgZeJcbniUVaR7gxLLvW8i) (3,2,1の順で開発予定or要相談)
    - webのアイデア詳細(未定)
- Normal?(未定)(開発期間によって変更)
    - text
    - コピペ
    - リサイズ
    - 基本的な図形の描画
    - 定規

## シェア(画像 , link)
- [konva-storage-data-url](https://konvajs.org/docs/data_and_serialization/Stage_Data_URL.html)
- [Twitter](https://miraiteki.life/develop/2019/tiwtter-share-button-with-image-attachment/)
