# readme

## links


- [Whimsical folder](https://whimsical.com/recursion-group-k-UW7zYZzDjCJWgqJYySxXBv)
- [Notion 使うか未定](?)
- [Vue CLI install](https://cli.vuejs.org/guide/installation.html)
- [Vue.js devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)

## commands


|                                         | 用途                 |
|-----------------------|-----------------------|
|git clone {url}                          |	リモートからローカルにコピー    | 
|git add .	                              |                         |
|git commit 	                            |                         |
|git push	                                |                         |
|git switch	                              | ブランチ切り替え            |
|git switch -c	                          | ブランチ作成&切り替え        |
|git checkout {branch}                    | ブランチ切り替え            |
|git checkout -b {branch}                 |	ブランチ作成&切り替え        |
|git pull --no-ff develop	develop         | ブランチを今のブランチにmerge | 
|git pull origin develop --rebase	        | ブランチを最新の状態にする    | 

最後のコマンドは結構使うことになると思います。
developに限りませんが、複数人だと、自分が作業してなくても更新されるので、リモートの最新を取り込みたいって時に使います。
`--rebase`ってしているのは `git pull` をしたときに不要なコミットを防ぐためです。本来の用途は違いますが。

## github
- [プルリクの作成](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
- [プルリクのレビューリクエスト](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/requesting-a-pull-request-review)
- [チーム開発におけるプルリクのお作法](https://qiita.com/ikuwow/items/fb52a54c086398eb5b92)
