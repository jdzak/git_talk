# Git Overview

This is an overview of the git version control system for the EDW. You can find
me at https://github.com/jdzak/git_talk.

## Overview

1. mkdir simpsons_characters
2. `touch README.md`
3. `git init`
4. `git add README.md`
5. `git commit -m "Added the best simpsons characters"`
6. `gitx`
7. https://github.com/new
  * simpsons_characters
8. `git remote add origin git@github.com:jdzak/simpsons_characters.git`
9. `git push -u origin master`
10. `gitx`
11. `git checkout -b side_characters`
12. `gitx`
13. `git add README.md`
14. `git commit -m"Added the best simpsons side characters"
15. `gitx`
16. `git checkout master`
17. `git merge side_characters`
18. `gitx`

## Git References

* https://try.github.io/levels/1/challenges/1
* https://www.codeschool.com/courses/try-git
* https://help.github.com/articles/what-are-other-good-resources-for-learning-git-and-github
* http://danielkummer.github.io/git-flow-cheatsheet/
* http://blog.interlinked.org/static/images/git/high-level-commands.png