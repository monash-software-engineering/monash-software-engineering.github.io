Monash Software Engineering Research Group Web Site 
================================

Setup
-----

1. Install the dependencies. You will need [Python](https://www.python.org/), [bibble](https://github.com/sampsyo/bibble) (`pip install bibble`), and [Jekyll](https://jekyllrb.com/) (`gem install jekyll`).
2. Fork this repository on GitHub.
3. Clone the fork to your own machine: `git clone git@github.com:yourgroup/research-group-web.git`.
4. Add an "upstream" remote for the original repository so you can stay abreast of bugfixes: `git remote add upstream git://github.com/uwsampa/research-group-web.git`.
5. Customize. Start with the `_config.yml` file, where you enter the name of the site and its URL.
6. Type `make` to build the site and then run `make serve` to view your site locally(http://0.0.0.0:5000). Note that the list of publications is in `bib/pubs.bib`. Typing `make` will generate `pubs.html`, which contains a pretty, sorted HTML-formatted list of papers. The public page, `publications.html`, also has a link to download the original BibTeX.
7. Keep adding content. See below for instructions for each of the various sections.
8. Periodically pull from the upstream repository: `git pull upstream master`.


Update the website
----------------------

* To update the *Description* in the homepage, please add the content in `index.html`;
* To update the *News*, please add Markdown file in `_posts`;
* To update the *People*, please add/delete the person profile in `_data/people.yml`;
* To update the *Research Area*, please add the markdown file in `_projects`;
* To update the *Publication*, please add your bibtex into `bib/pubs.bib`. Note that all the bibtex record must contain the attibute **Month**, and you can add the URL attibute to your bibtex.
* To update the *Achievement*, please revise the file `achievement.md`;


Others
-----------------------
For more questions, please contact me by Chunyang.Chen@monash.edu, or propose issues to the project.

We appreciate the <a href="https://github.com/uwsampa/research-group-web" target="_blank">template sharing</a> from University of Washington.
This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License][license].
[license]: https://creativecommons.org/licenses/by-nc/4.0/

