# Git の勉強

- git add コマンドで、リポジトリに変更情報を追加する
  - このことをステージングと言う
- git commit コマンドで、ステージングされた情報にコメントを付けてコミットできる
- git push コマンドで、ローカルのコミットをリモートのリポジトリに反映できる
- git tag コマンドでコミットにタグ付けできる
  - タグを追加すると、GitHub ではダウンロード用の zip ファイルが自動で作られる

# Git へのcommitとpush手順
git status
git add ファイルorディレクトリ名
git commit -m "コミットメッセージの内容"
git push origin main

以上でGitHubへと変更が適用される
