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
	b = branch
	bd = branch -d
	ch = checkout
	chb = checkout -b
	c = commit
	ca = commit -a
	cv = commit -v
	cav = commit -av
	d = diff
	ds = diff --staged
	l = log
	m = merge
	mf = merge --ff-only
	p = push
	pu = push -u origin
	r = reset
	s = status
	st = stash
	sta = stash apply
	stl = stash list
</pre>
