1. git clone
2. https://github.com/tetsuokawada-obj/Artist_koharu_html.git

3. git commit -m
4. fatal: not a git repository>>>ここはGitリポジトリじゃないよ

5. 今いるフォルダで Git初期化してない
6. 一連の流れ
cd プロジェクトフォルダ
git init
git add .　保存対象にするよ
git commit -m "初めてのコミット"

7. 全体流れ
ファイル作成・編集↓
git status（変更内容確認）↓
git pull --rebase（GitHubの最新状態を取得）↓
git add .（準備）↓
git commit -m "メッセージ"（保存）↓
git push（GitHubに送る）

8. 毎度操作のテンプレ
git status
git pull --rebase
git add .
git commit -m "〇〇更新"
git push




