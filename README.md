# freebsd.make.release
build a FreeBSD release, from svnsync to iso images
- update/create local svn repo, checkout src, buildworld, make world, etc.
- run './make.release' and follow the prompts.
- your choices are saved in ~/.make.release and loaded as default on your next run.
- for now it needs to run as root.  hope to change that soon
