# Incubaker.com

The first website I've switched over to use github pages via the `gh-pages` branch.

To download a local copy of this site

	git clone https://github.com/incubaker/incubaker.com

To download the submodules

	git submodule update --init

To push run

	git push origin master
	git push origin gh-pages

If the `gh-pages` branch does not exist

	git branch gh-pages	
	
If `.git/config` contains

	push = +refs/heads/master:refs/heads/gh-pages
	push = +refs/heads/master:refs/heads/master
	
in the `[remote "origin"]` section then all that is needed is to push to origin and it will push to both.

	git push origin 