Source files with PDF and HTML versions of Curriculum Vita.

To build both the HTML and PDF versions run:

````
latexmk
latexmk -pdf
````


To push to main repo and submodule remote

1. Commit submodule
2. Commit main repo
3. Push submodule: `git push origin HEAD:master`
3. Pussh main repo as you would normally
