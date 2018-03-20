# GitAliases
a list of my git aliases.

Copy your git.exe and rename it as g.exe for even faster git interaction.

Find your .gitconfig
Can use:
git config --list --show-origin

Mine lives in my home directory:
C:/Users/myName/.gitconfig

Put the following into your .gitconfig:
[alias]
	s = status
	a = add
	c = commit
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
