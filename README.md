# GitAliases
a list of my git aliases.

For even faster git ineraction check out my project <a href="https://github.com/KyleScharnhorst/git-to-g">git-to-g</a> for using g instead of git. E.g., g s instead of git status or git s.

Find your .gitconfig
Can use:
git config --list --show-origin

Mine lives in my home directory:
C:/Users/myName/.gitconfig

Put the following into your .gitconfig:
<pre>
[alias]
	a = add
	ap = add --patch
	au = add --update
	b = branch
	bd = branch --delete
	bl = branch --list
	ch = checkout
	chb = checkout -b
	chp = checkout --patch
	c = commit
	ca = commit --all
	cv = commit --verbose
	cav = commit --all --verbose
	d = diff
	ds = diff --staged
	l = log
	m = merge
	mf = merge --ff-only
	p = push
	pu = push --set-upstream origin
	r = reset
	rb = rebase
	rbc = rebase --continue
	s = status
	st = stash
	sta = stash apply
	stl = stash list
</pre>
