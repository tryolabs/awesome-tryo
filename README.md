# Awesome Tryo

A curated list of books, libraries, apps and papers we love at [Tryolabs][tryo].

# Training

The training period at Tryolabs is at least two weeks. Its goal is to get up to
speed with the tools the company uses. This repo contains a list of tutorials
and documentation useful for becoming familiar with the Django/Python ecosystem.

During the training period, we recommend doing at least an hour a day of pairing
with a mentor who has experience in the team, to get to know the work process
and the tools. The goal is to get the mentor to coment on the tasks they are
doing to the person in training.

# Development Tools

## virtualenv and virtualenvwrapper

A very useful development tool that lets us create isolated Python environments
for every project, isolating the set of libraries used in the project from the
system.

* [virtualenv][venv]
* [virtualenvwrapper][venv-wrapper]

# Standards and Conventions

The [PEP8][pep8] is the definitive reference for Python coding style. The
[pep8][pep8-py] package can be used to scan code and find parts that don't
conform to the PEP8 standard.

# Databases

## Relational

Just use [Postgres][postgres]. It's not just a database, it's a complete
"relational database framework" that provides [full-text search][postgres-text],
[GIS][postgres-gis] and extensive documentation of every knob and lever.

# Books

## Machine Learning

* [Machine Learning: The Art and Science of Algorithms that Make Sense of Data][ml-book]
* [Learning scikit-learn: Machine Learning in Python][learning-scikit-learn]

[tryo]: http://tryolabs.com/

[venv]: https://virtualenv.pypa.io/en/latest/
[venv-wrapper]: http://virtualenvwrapper.readthedocs.org/en/latest/

[pep8]: http://www.python.org/dev/peps/pep-0008/
[pep8-py]: https://pypi.python.org/pypi/pep8

[postgres]: http://www.postgresql.org/
[postgres-text]: http://www.postgresql.org/docs/8.3/static/textsearch.html
[postgres-gis]: http://postgis.net/

[ml-book]: http://www.cambridge.org/us/academic/subjects/computer-science/pattern-recognition-and-machine-learning/machine-learning-art-and-science-algorithms-make-sense-data
[learning-scikit-learn]: https://www.packtpub.com/big-data-and-business-intelligence/learning-scikit-learn-machine-learning-python
