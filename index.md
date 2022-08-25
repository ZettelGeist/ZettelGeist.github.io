---
layout: home
---

ZettelGeist is a terminal-based application for indexing and retrieving text files.
It is a general-purpose and scholarly note-taking system for people who want to create, store, retrieve, and transform a lot of information.

Inspired by the [Zettelkasten](https://en.wikipedia.org/wiki/Zettelkasten) method of note-taking, ZettelGeist can emulate the data structure of an old-school research notecard.
It can also be implemented as a diary, drafts folder, personal archive, or the knowledge base of a research lab.

# Features

- manage large amounts of textual data in Markdown and YAML formats
- lightweight and super fast
- apply the metadata fields that fit your data and workflow
- search by tags, summary, bibkey, or a range of other fields
- use your preferred text editor
- customizable output

# Installation

Install the ZettelGeist package within an active Python virtual environment:

```
$ source venv/bin/activate
$ pip install zettelgeist
```

Documentation on getting started is available in [the wiki](https://github.com/ZettelGeist/zettelgeist/wiki/Installing-the-Tools).

# Summary

If you write in Markdown and want a powerful lightweight indexing system to run alongside `git` version control, ZettelGeist may be for you.
Documents to be indexed by ZettelGeist are each supplied with YAML metadata.
Metadata may include tags, a bibliographical citation, title, and summary, among other fields.
ZettelGeist imports the Markdown documents on a working tree into a database.
The database mirrors the contents of the working tree and forms the target of queries.

Metadata can be edited directly with your preferred text editor or batch-edited with ZettelGeist, by applying transformations to documents matching a given query.
The ZettelGeist publication option allows the output of queries to be formatted and recombined.
In this way large complex documents can be constructed directly from modular components.

ZettelGeist is in active development and seeks user feedback.

# Resources

- [wiki](https://github.com/ZettelGeist/zettelgeist/wiki)
- [issues](https://github.com/ZettelGeist/zettelgeist/issues)

# Creators

ZettelGeist is the creation of [George K. Thiruvathukal](https://gkt.cs.luc.edu/)
  in collaboration with [David B. Dennis](https://www.luc.edu/history/people/facultyandstaffdirectory/facultybytheme/politics/dennisdavidb.shtml)
  and [Ian Cornelius](https://icornelius.github.io/).
