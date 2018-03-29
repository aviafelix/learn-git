# How To...

* squash commits?
```sh
$ git rebase -i HEAD~n
$ git rebase -i HEAD~n-1^
$ git rebase -i <commit-id>

# or:

$ git reset --hard HEAD~n
# or:
$ git reset --hard <commit-id>
# and then:
$ git merge --squash HEAD~{1}
```
