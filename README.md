git-setup
========

Simple `git init` wrapper to initialize git user's email and the right SSH key. Useful for managing multiple GitHub accounts.

See: [StackOverflow](http://stackoverflow.com/questions/4565700/specify-private-ssh-key-to-use-when-executing-shell-command-with-or-without-ruby)

Usage
-----

	git clone git@github.com/your/repo.git
  git setup

  # or
  mkdir new-repo && cd new-repo
  git setup


Installation
------------

	git clone https://github.com/ibolmo/git-setup.git
	ln -s $(pwd)/git-setup/git-setup ~/bin/git-setup # add to path


Requirements
------------
 * git: 2.10.x or greater
