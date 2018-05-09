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
	s = status
	a = add
	c = commit
	ca = commit -av
	cav = commit -av
	cv = commit -v
	p = push
	pu = push -u origin
	d = diff
	ds = diff --staged
	l = log
	b = branch
	bd = branch -d
	ap = add --patch
	ch = checkout
	chb = checkout -b
	r = reset
	m = merge
	mf = merge --ff-only
	st = stash
	sta = stash apply
	stl = stash list
</pre>
