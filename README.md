# test20210208syn
```
test20210208syn new@hub, and then importby lab
then web edit@hub, pullby lab
then web edit@lab, try to pullby lab(seems warning@pull of lab-diverge)
-//The default branch (main) has diverged from its upstream counterpart and could not be updated automatically.
and then pushby lab
---git version 2.21.0.windows.1
jqedit@lab
jqedit@hub  //git push   github main (without -u)
jqedit@hub-3//ps: gitlab-web-push is a 'git push --force' likely,be careful manually!!
---git version 2.10.0.windows.1(xp)
mxedit@lab
mxedit@hub //git remote add  xhub https://...;  and then pull-rebase/push xhub main
```

```
//mxedit@lab
//=network-error. ok,try again
Administrator@WWW-F367279F207 MINGW32 /c/cygwin2.2.1/home/Administrator/git.repo/gitlab/test20210208syn (main)
$ git pull -r
fatal: unable to access 'https://gitlab.com/asbcd20z/test20210208syn/': Unknown SSL protocol error in connection to gitlab.com:443
//=network-error. ok
Administrator@WWW-F367279F207 MINGW32 /c/cygwin2.2.1/home/Administrator/git.repo/gitlab/test20210208syn (main)
$ git push
Username for 'https://gitlab.com': asbcd20z
fatal: unable to access 'https://gitlab.com/asbcd20z/test20210208syn.git/': Unknown SSL protocol error in connection to gitlab.com:443
//=id/pw-error. ok
Administrator@WWW-F367279F207 MINGW32 /c/cygwin2.2.1/home/Administrator/git.repo/gitlab/test20210208syn (main)
$ git push  github main
Username for 'https://github.com': asbcd20z
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/asbcd20z/test20210208syn/'
//error. ok?
Administrator@WWW-F367279F207 MINGW32 /c/cygwin2.2.1/home/Administrator/git.repo/gitlab/test20210208syn (main)
$ git push
Username for 'https://gitlab.com': asbcd29z
remote: HTTP Basic: Access denied
fatal: Authentication failed for 'https://gitlab.com/asbcd20z/test20210208syn.git/'
//
Administrator@WWW-F367279F207 MINGW32 /c/cygwin2.2.1/home/Administrator/git.repo/gitlab/test20210208syn (main)
$ git --version
git version 2.10.0.windows.1
//
```
