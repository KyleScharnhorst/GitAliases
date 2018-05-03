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
	ap = add --patch
	b = branch
	bd = branch -d
	c = commit
	ca = commit -a
	cav = commit -av
	cv = commit -v
	ch = checkout
	chb = checkout -b
	d = diff
	ds = diff --staged
	l = log
	p = push
	pu = push -u origin
	r = reset
</pre>
