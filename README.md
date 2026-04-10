# tamesare-data-sapporo-opening
試されDATA SAPPOROのオープニング資料

## スライドの閲覧方法
GitHub Pagesの設定を有効にしている場合、以下のURLから各回のスライドを閲覧できます。
`https://<ユーザー名>.github.io/tamesare-data-sapporo-opening/<ファイル名>.html`

## 開発・更新手順
新しい勉強会の資料を追加する場合は、以下の手順で行います。

1.  既存の `.qmd` ファイルをコピーして新規作成する。
2.  内容を編集する。
3.  Quartoを使用してHTMLへレンダリングする。
    ```bash
    quarto render <ファイル名>.qmd
    ```
4.  変更をGitHubへプッシュする。