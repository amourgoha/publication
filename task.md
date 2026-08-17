task: the workflow of github name sync is failed to sync fork, an error show '
Run repository_metadata="$(gh api "repos/${GITHUB_REPOSITORY}")"
From https://github.com/hehonghui/awesome-english-ebooks
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> upstream/master
hint: Diverging branches can't be fast-forwarded, you need to either:
hint:
hint: 	git merge --no-ff
hint:
hint: or:
hint:
hint: 	git rebase
hint:
hint: Disable this message with "git config set advice.diverging false"
fatal: Not possible to fast-forward, aborting.
Error: Process completed with exit code 128.'
fix it