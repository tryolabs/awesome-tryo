# Awesome Tryo

A curated list of books, libraries, apps and papers we love at [Tryolabs][tryo].

[tryo]: http://tryolabs.com/

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

[venv]: https://virtualenv.pypa.io/en/latest/
[venv-wrapper]: http://virtualenvwrapper.readthedocs.org/en/latest/

## cocoapods

Package manager for iOS projects. Handle the setup and update of XCode projects
to speed up the integration of new components.

* [cocoapods][cocoapods]

[cocoapods]:http://cocoapods.org/

## nomad

CLI for iOS projects. Has various tools to perform common task from the command
line (ex: generate, sign and ditribute OTA an ipa)

* [nomad][nomad]

[nomad]:http://nomad-cli.com/

## Vagrant

[Vagrant][vagrant] is a tool for creating isolated, reproducible development
environments using virtual machines.

[vagrant]: https://www.vagrantup.com/

## Source Control

Just use [git][git]. A good resource is the [Pro Git][pro-git] book by Scott
Chacon, and [GitHub's help site][gh-help].

[git]: http://git-scm.com/
[pro-git]: http://git-scm.com/book/en/v2
[gh-help]: https://help.github.com/articles/good-resources-for-learning-git-and-github/

# Standards and Conventions

The [PEP8][pep8] is the definitive reference for Python coding style. The
[pep8][pep8-py] package can be used to scan code and find parts that don't
conform to the PEP8 standard.

[pep8]: http://www.python.org/dev/peps/pep-0008/
[pep8-py]: https://pypi.python.org/pypi/pep8

# Deploying

We use [Ansible][ansible] for all our deployment and server orchestration tasks.

[ansible]: http://www.ansible.com/home

# Databases

## Relational

Just use [Postgres][postgres]. It's not just a database, it's a complete
"relational database framework" that provides [full-text search][postgres-text],
[GIS][postgres-gis] and extensive documentation of every knob and lever.

[postgres]: http://www.postgresql.org/
[postgres-text]: http://www.postgresql.org/docs/8.3/static/textsearch.html
[postgres-gis]: http://postgis.net/

## NoSQL

Are you *sure* Postgres can't do what you want?

### Document

* [CouchDB][couch]

[couch]: http://couchdb.apache.org/

### Key-Value

* [Redis][redis]
* [Dynamo][dynamo]
* [Riak][riak]

[redis]: http://redis.io/
[dynamo]: http://aws.amazon.com/dynamodb/
[riak]: http://basho.com/riak/

### Graph

* [Neo4j][neo4j]

[neo4j]:http://neo4j.com/

# Libraries

## Machine Learning

* [SciPy][scipy]
* [scikit-learn][sk-learn]
* [Natural Language Toolkit][nltk]
* [NumPy][numpy]

[scipy]: http://www.scipy.org/
[sk-learn]: http://scikit-learn.org/stable/
[nltk]: https://www.djangoproject.com/
[numpy]: http://www.numpy.org/

## Web

* [Django][django]
* [Django REST framework][django-rest]
* [Scrapy][scrapy]

[django]: https://www.djangoproject.com/
[django-rest]: http://www.django-rest-framework.org/
[scrapy]: http://scrapy.org/

# Books

This list of books represents, in our opinion, a good balance between theory and
practice. We don't expect everyone to read all of these, rather, they should
take a few books from this common list.

## Machine Learning

* [Machine Learning: The Art and Science of Algorithms that Make Sense of Data][ml-book]
* [Learning scikit-learn: Machine Learning in Python][learning-scikit-learn]
* [The Elements of Statistical Learning: Data Mining, Inference, and Prediction][elements-learning]
* [Principles of Data Mining][principles-dm]
* [Foundations of Statistical Natural Language Processing][foundations-nlp]

[ml-book]: http://www.cambridge.org/us/academic/subjects/computer-science/pattern-recognition-and-machine-learning/machine-learning-art-and-science-algorithms-make-sense-data
[learning-scikit-learn]: https://www.packtpub.com/big-data-and-business-intelligence/learning-scikit-learn-machine-learning-python
[elements-learning]: http://statweb.stanford.edu/~tibs/ElemStatLearn/
[principles-dm]: http://www.springer.com/computer/database+management+%26+information+retrieval/book/978-1-4471-4883-8
[foundations-nlp]: http://nlp.stanford.edu/fsnlp/

## Information Retrieval

* [Managing Gigabytes: Compressing and Indexing Documents and Images][managing-gb]
* [Introduction to Information Retrieval][intro-ir]
* [Modern Information Retrieval][modern-ir]
* [Information Retrieval: Searching in the 21st Century][ir-search-book]
* [Information Retrieval: Algorithms and Heuristics][ir-algorithms]

[managing-gb]: http://www.amazon.com/Managing-Gigabytes-Compressing-Multimedia-Information/dp/1558605703
[intro-ir]: http://nlp.stanford.edu/IR-book/
[modern-ir]: http://www.mir2ed.org/
[ir-search-book]: http://www.wiley.com/WileyCDA/WileyTitle/productCd-0470027622.html
[ir-algorithms]: http://www.springer.com/computer/ai/book/978-1-4020-3003-1

## Computer Vision

* [Concise Computer Vision][concise-cv]
* [Computer Vision: Algorithms and Applications][cv-algorithms]
* [Learning OpenCV: Computer Vision in C++ with the OpenCV Library][opencv-book]

[concise-cv]: http://www.springer.com/computer/image+processing/book/978-1-4471-6319-0
[cv-algorithms]: http://www.springer.com/computer/image+processing/book/978-1-84882-934-3
[opencv-book]: http://shop.oreilly.com/product/0636920022497.do

## Scala

* [Play for Scala][play-for-scala]
* [Scala by Example][scala-by-example]

[play-for-scala]: http://www.manning.com/hilton/
[scala-by-example]:http://www.scala-lang.org/docu/files/ScalaByExample.pdf

## Software Architecture

* [The Architecture of Open Source Applications][aos-book]

[aos-book]: http://aosabook.org/en/index.html

## Programming Language

* [Structure and Interpretation of Computer Programs][sicp]

[sicp]:http://mitpress.mit.edu/sicp/full-text/book/book.html

# Papers

## Information Retrieval

* [An Object-Oriented Architecture for Text Retrieval][oo-text-retrieval]

[oo-text-retrieval]: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.53.820&rep=rep1&type=pdf

## General

* [Functional Geometry][func-geom]
* [Pictures: A simple structured graphics model][pictures-paper]

[func-geom]: https://cs.au.dk/~hosc/local/HOSC-15-4-pp349-365.pdf
[pictures-paper]: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.48.1524&rep=rep1&type=pdf
