This repository's existence is a hack.

My old website had a /Releases/ directory with a whole bunch of binary
releases. Github doesn't have any way to generate a 301 so I could map those to
the github Files section of a project, so instead, let's create a Releases
project which will show up on my github pages 

All files go on the gh-pages branch.

All releases of VitaminSEE older than 0.7.1.2 are now symlinks to
0.7.1.2. (0.7.2 was more of a dump of what was in svn than a release...).

I am doing the same with all mac versions of rlvm prior to 0.6.2, which is the
most stable yet. People are downloading more outdated versions than recent
releases (0.2 still gets more than 20 downloads a month!)
