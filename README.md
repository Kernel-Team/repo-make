repo-make
=========

repo-make is a small tool which allows you to autobuild a set of PKGBUILD's into a working repository.

repo-make has been created with version control in mind. The developer adds a "repo-make.conf" file to his repository which describes how to build his PKGBUILD's. If the developer changes something in the repository, then users may just fetch the latest changes and run "repo-make" to create/update a local repository.
