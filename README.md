## Released webpage

[blog.abgup.com](https://blog.abgup.com)

## Local build instructions

```python
$ `mkdocs serve`        # Start the live-reloading docs server.
$ `mkdocs build`        # Build the documentation site.
$ `mkdocs -h`           # Print help message and exit.
$ `mkdocs gh-deploy`    # Push changes from main branch to gh-pages
```

Open localhost in browser (http://127.0.0.1:8000/)


## Background

#### Reason for starting:

- Bob (friend) talked about another repo porting over to mkdocs and wanted me to explain what they doing.
- I explained it and thought it was a great idea so thought I might use it for my own notes/blogs that have been on hiatus.

--- 

#### Discussion

- I realized after I starting coding this blog that the static site generator I use (jekyll) was just a more common/powerful version of it. 
- However, nested folders in jekyll isn't natively supported so am continuing the blog with this framework.

--- 

#### Future:

- Using gitsubmodules for blogs
- Hosting them on personal website via Jekyll framework ( [abgup.com](abgup.com) )
- Using medium.com api to push to medium after post

## Project layout

```python
mkdocs.yml    # The configuration file.
docs/
    index.md  # The documentation homepage.
    ...       # Other markdown pages, images and other files.
site/         # local build files
    css/
    ,..
```

## Frameworks docs


[mkdocs.org](https://mkdocs.com)

