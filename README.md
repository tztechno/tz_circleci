# tz_git_circleci

```
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃                                                                                                       ┃
┃  circleci local execute                                                                               ┃
┃                                                                                                       ┃
┃                                                                                                       ┃
┃                                                                                                       ┃
┃                                                                                                       ┃
┃  Usage:                                                                                               ┃
┃         circleci local execute <job-name> [flags]                                                     ┃
┃                                                                                                       ┃
┃  Local Flags:                                                                                         ┃
┃                                                                                                       ┃
┃       --branch string                git branch                                                       ┃
┃       --build-agent-version string   The version of the build agent image you want to use. This can b ┃
┃ e                                                                                                     ┃
┃ configured by writing in $HOME/.circleci/build_agent_settings.json: '{"LatestSha256":"<version-of-bui ┃
┃ ld-                                                                                                   ┃
┃ agent>"}'                                                                                             ┃
┃       --checkout-key string          git checkout key (default "~/.ssh/id_rsa")                       ┃
┃   -c, --config string                config file (default ".circleci/config.yml")                     ┃
┃       --docker-socket-path string    path to the host's docker socket (default "/var/run/docker.sock" ┃
┃ )                                                                                                     ┃
┃   -e, --env -e VAR=VAL               set environment variables, e.g. -e VAR=VAL                       ┃
┃   -h, --help                         help for execute                                                 ┃
┃       --index int                    node index of parallelism                                        ┃
┃       --node-total int               total number of parallel nodes (default 1)                       ┃
┃       --org-id string                organization id, used when a config depends on private orbs      ┃
┃ belonging to that org                                                                                 ┃
┃   -o, --org-slug string              organization slug (for example: github/example-org), used when a ┃
┃ config depends on private orbs belonging to that org                                                  ┃
┃       --repo-url string              git URL                                                          ┃
┃       --revision string              git revision                                                     ┃
┃       --skip-checkout                use local path as-is (default true)                              ┃
┃       --temp-dir string              path to local directory to store temporary config files          ┃
┃   -v, --volume stringArray           volume bind-mounting                                             ┃
┃                                                                                                       ┃
┃  Global Flags:                                                                                        ┃
┃                                                                                                       ┃
┃       --host string         URL to your CircleCI host, also CIRCLECI_CLI_HOST (default                ┃
┃ "https://circleci.com")                                                                               ┃
┃       --skip-update-check   Skip the check for updates check run before every command.                ┃
┃       --token string        your token for using CircleCI, also CIRCLECI_CLI_TOKEN                    ┃
┃                                                                                                       ┃
┃                                                                                                       ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
```

---

# git操作 error collection

---

git init: 新しいGitリポジトリを初期化します。
git init

git clone: リモートリポジトリを複製します。
git clone <repository_url>

git add: 変更をステージングエリアに追加します。
git add <file>

git commit: ステージングエリアの変更をコミットします。
git commit -m "コミットメッセージ"

git status: 現在のリポジトリのステータスを表示します。
git status

git pull: リモートリポジトリから最新の変更を取得します。
git pull

git push: ローカルの変更をリモートリポジトリにプッシュします。
git push

git branch: ブランチの一覧を表示します。
git branch

git checkout: ブランチを切り替えます。
git checkout <branch_name>

git merge: ブランチを統合します。
git merge <branch_name>

git log: コミット履歴を表示します。
git log

git remote: リモートリポジトリを管理します。
git remote -v

git fetch: リモートリポジトリから情報を取得しますが、ローカルの変更は行いません。
git fetch

git diff: 変更内容を表示します。
git diff
