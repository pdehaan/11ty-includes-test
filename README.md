# 11ty-includes-test

Testing permalinks and includes in Eleventy.

Per https://github.com/11ty/eleventy/issues/889, this tries to create a bunch of posts in the docs/examples/* directory based on different `{% include "./relative-file.html" %}` calls.

# Building the site

To build the site, clone the repo and run <kbd>npm run 11ty:build</kbd>. The generated output files are in the root ./_site/ directory.
