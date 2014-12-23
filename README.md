qgp
===

qgp = quick git push = git add ., git commit "custom message", git push


## setup

In this repo, you'll find a sample `qgp.sh` containing the script. If you want to execute the function defined there as a command, then add it to your `.bashrc`, `.zshrc`, or whatever your shell uses!


## usage

`qgp "added firefox support"`

really executes

```bash
git add .
git commit -a -m "added firefox support"
git push origin master
```
