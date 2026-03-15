## Scripts
a collection of useful scripts for various tasks.
<hr>

[Chris Titus Tech's Windows Utility](https://github.com/ChrisTitusTech/winutil)<br>
Install Programs, Tweaks, Fixes, and Updates.

<hr>
Clone entire GitHub profile / Organization
```py
gh repo list ORGNAMEHERE --limit 4000 | while read -r repo _; do
  gh repo clone "$repo" "$repo"
done
```
<hr>

[WinMasterBlocker](https://gist.github.com/ph33nx/0ed14724213c4cc467c85826c9dca908)<br>
Block All Adobe connections via Firewall.
