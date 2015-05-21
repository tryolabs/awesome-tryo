# Awesome Tryo

A curated list of books, libraries, apps and papers we love at
[Tryolabs][tryo]. We work with blazing startups and help them build complex
projects using Python, NLP & Machine Learning.

[tryo]: http://tryolabs.com/

# Overview

We create amazing Internet & Mobile products for blazing startups. We combine
the python ecosystem with machine learning and natural language processing
technologies to create heavy backend apps with artificial intelligence
components. We follow agile methodologies in order to develop MVPs and full
products the lean way.

## Training

The training period at Tryolabs is at least two weeks. Its goal is to get up to
speed with the tools the company uses. This repo contains a list of tutorials
and documentation useful for becoming familiar with the Django/Python ecosystem,
as well as some ML and NLP techniques.

During the training period, we recommend doing at least an hour a day of pairing
with a mentor who has experience in the team, to get to know the work process
and the tools. The goal is to get the mentor to coment on the tasks they are
doing to the person in training.

# Development Tools

## Python

### virtualenv and virtualenvwrapper

A very useful development tool that lets us create isolated Python environments
for every project, isolating the set of libraries used in the project from the
system.

* [virtualenv][venv]
* [virtualenvwrapper][venv-wrapper]

[venv]: https://virtualenv.pypa.io/en/latest/
[venv-wrapper]: http://virtualenvwrapper.readthedocs.org/en/latest/

## iOS

### cocoapods

Package manager for iOS projects. Handle the setup and update of XCode projects
to speed up the integration of new components.

* [cocoapods][cocoapods]

[cocoapods]:http://cocoapods.org/

### nomad

CLI for iOS projects. Has various tools to perform common task from the command
line (ex: generate, sign and ditribute OTA an ipa)

* [nomad][nomad]

[nomad]:http://nomad-cli.com/

## Other

### Vagrant

[Vagrant][vagrant] is a tool for creating isolated, reproducible development
environments using virtual machines. It is usually used with VirtualBox, but
supports VMWare and other virtualization systems.

[vagrant]: https://www.vagrantup.com/

### Docker

[Docker][docker] is a tool for creating and managing
[software containers][containers].

[docker]: https://www.docker.com/
[containers]: http://en.wikipedia.org/wiki/Operating-system-level_virtualization

### Metamon

[Metamon][metamon] is a tool to automatically set up an isolated execution
environment for Django applications.

[metamon]:https://github.com/tryolabs/metamon

## Source Control

Just use [git][git]. A good resource is the [Pro Git][pro-git] book by Scott
Chacon, and [GitHub's help site][gh-help].

[git]: http://git-scm.com/
[pro-git]: http://git-scm.com/book/en/v2
[gh-help]: https://help.github.com/articles/good-resources-for-learning-git-and-github/

## Editors and IDEs

* [Emacs][emacs]
* [PyDev][pydev]

[emacs]: http://www.gnu.org/software/emacs/
[pydev]: http://pydev.org/

# Standards and Conventions

The [PEP8][pep8] is the definitive reference for Python coding style. The
[pep8][pep8-py] package can be used to scan code and find parts that don't
conform to the PEP8 standard.

With Emacs, the [emacs-pep8] package can be used to run the pep8.py script.

[pep8]: http://www.python.org/dev/peps/pep-0008/
[pep8-py]: https://pypi.python.org/pypi/pep8
[emacs-pep8]: https://marmalade-repo.org/packages/pep8

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
* [RethinkDB][rethinkdb]
* [Elasticsearch][elasticsearch]

[couch]: http://couchdb.apache.org/
[rethinkdb]: http://rethinkdb.com/
[elasticsearch]: http://www.elasticsearch.com/products/elasticsearch/

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
* [Bayesian Reasoning and Machine Learning][bayesian-reasoning]

[ml-book]: http://www.cambridge.org/us/academic/subjects/computer-science/pattern-recognition-and-machine-learning/machine-learning-art-and-science-algorithms-make-sense-data
[learning-scikit-learn]: https://www.packtpub.com/big-data-and-business-intelligence/learning-scikit-learn-machine-learning-python
[elements-learning]: http://statweb.stanford.edu/~tibs/ElemStatLearn/
[principles-dm]: http://www.springer.com/computer/database+management+%26+information+retrieval/book/978-1-4471-4883-8
[foundations-nlp]: http://nlp.stanford.edu/fsnlp/
[bayesian-reasoning]: http://web4.cs.ucl.ac.uk/staff/D.Barber/pmwiki/pmwiki.php?n=Brml.HomePage

## Information Retrieval

* [Managing Gigabytes: Compressing and Indexing Documents and Images][managing-gb]
* [Introduction to Information Retrieval][intro-ir]
* [Information Retrieval: Algorithms and Heuristics][ir-algorithms]

[managing-gb]: http://www.amazon.com/Managing-Gigabytes-Compressing-Multimedia-Information/dp/1558605703
[intro-ir]: http://nlp.stanford.edu/IR-book/
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
* [The Problem with Threads (Threads are Evil)][threads-are-evil]

[func-geom]: https://cs.au.dk/~hosc/local/HOSC-15-4-pp349-365.pdf
[pictures-paper]: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.48.1524&rep=rep1&type=pdf
[threads-are-evil]: http://www.eecs.berkeley.edu/Pubs/TechRpts/2006/EECS-2006-1.pdf

# Web Design

## Aggregators

* [Dribbble][dribbble]
* [siteInspire][site-inspire]
* [Flat UI Design][flat-ui]
* [Mobile Patterns][mobile-pats]

[dribbble]: https://dribbble.com/
[site-inspire]: http://www.siteinspire.com/
[flat-ui]: http://fltdsgn.com/
[mobile-pats]: http://www.mobile-patterns.com/

## Icons

* [Mfizz font][mfizz]
* [Devicons][devicons]
* [Ikons][ikons]
* [Icomoon][icomoon]
* [Iconic][iconic]

[mfizz]: http://fizzed.com/oss/font-mfizz
[devicons]: http://vorillaz.github.io/devicons/#/dafont
[ikons]: http://ikons.piotrkwiatkowski.co.uk/
[icomoon]: https://icomoon.io/
[iconic]: https://useiconic.com/icons/

## Libraries and Resources

* [Device mockups][device-mockups]
* [Browser logos][browser-logos]
* [SweetAlert][sweet-alert]
* [Grid forms][grid-forms]

[device-mockups]: https://github.com/pixelsign/html5-device-mockups
[browser-logos]: https://github.com/paulirish/browser-logos
[sweet-alert]: https://github.com/t4t5/sweetalert
[grid-forms]: http://kumailht.com/gridforms/

# Tech Stack

First things first: Machines are meant to be identical. [Ansible][ansible]
provisions your local [Vagrant][vagrant] box the same way it provisions a
server. This way the production environment is the same as the development one,
and we avoid hard to find bugs while being fairly certain that if something
works in dev, it will work in prod.

Specifically, machines look like this:

* The application is run inside a [virtualenv][venv], even if it's the only
  application in the server. This makes it easy to add other applications should
  the need arise, for instance, you might want to run an IPython Notebook server
  with a Notebook that provides some analytics and charts of the data in your
  database, without contaminating the app's environment with IPython's
  dependencies.

* [Nginx][nginx] is used as a reverse proxy, sending requests from the Internet
  to the Django server and responses the other way around. Nginx can take care
  of load balancing, caching, HTTP acceleration and some degree of security.

* [Supervisor][supervisord] is used to keep the actual application server
  running, as well as running other scripts or processes. Every process is
  logged to disk for debugging.

* [Postgres][postgres] is the database, of course.

Our tech stack looks roughly like this on most projects:

![Stack](https://rawgithub.com/tryolabs/awesome-tryo/master/stack.svg?raw=true)

This is, of course, an approximation. Some projects use NoSQL databases in
addition to relational ones, others use other things like message queues, some
use specific tools like [Varnish][varnish] instead of Nginx for HTTP
acceleration.

[nginx]: http://nginx.org/
[supervisord]: http://supervisord.org/
[varnish]: https://www.varnish-cache.org/
