# latex-devcontainer-termpaper

DevContainer でタームペーパーを執筆するためのテンプレートです。

Docker と VSCode さえあれば、ローカルに TexLive を入れずに編集することができます。

## Usage

1. 右上の "Use This Template" から、このリポジトリを自分のアカウントに複製する
2. VSCode に `Dev Container` 拡張機能を導入する
3. VSCode でリポジトリを開き、左下の `> <` アイコンをクリックして `Reopen in Container` を選択
4. `main.tex` を編集し保存すると、自動で `main.pdf` が生成される
5. 参考文献はBibTeXを利用して `cites.bib` に、画像は `img` ディレクトリに入れて適宜 `main.tex` からリンクする
