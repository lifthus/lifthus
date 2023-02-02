### Changing commit info ###

```git rebase -i --root```
<br>
Terminal shows commit history. Then change "pick" of any commit you wanna change to "edit" and go out with :wq command.
<br><br>
```git commit --amend```
<br>
now your current git state go back to oldest "edit" commit. then type the command above, you can change commit message.
and with commands like " git commit --amend --author="lifthus <lifthus531@gmail.com>" , you can change more specific things.
<br><br>

```git rebase --continue```
<br>
after the commit is changed, do rebase with it. then you go to next "edit" state.
<br><br>

```git push -f```
<br>
push to the remote repository forcefully.
<br><br>
