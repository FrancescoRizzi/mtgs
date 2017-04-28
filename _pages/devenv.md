---
title: "MTGS - DevEnv"
permalink: "devenv.html"
---

# DevEnv

For those interested in building MTGS locally (perhaps as a clone so that you can modify it, or contribute to it), here's how you can set up a local development environment.

## Prerequisites

* **OS:**<br />
   *Shouldn't matter*, unless stated otherwise. For the records, I'm using either **MacOS Sierra (10.12.4)**, or **MS Windows 7 (64-bit)**
* **Text Editor/IDE:**<br />
   *Your choice*, of course. I recommend picking a modern editor that -*at a minimum*- lets you configure the handling of *tabs vs spaces* according to your preference (especially for the Python source code). For instance: [Sublime Text](https://www.sublimetext.com/), [Brackets](http://brackets.io/), [Atom](https://atom.io/).
* **Python:** (if you plan to build and/or run the Python scripts)<br />
   Unless otherwise stated, assume [Python 2.7.x](https://www.python.org/downloads/). If you're setting up a Python environment for the first time, consider reading the page for your OS:
   * [Using Python on Macintosh](https://docs.python.org/2/using/mac.html)
   * [Using Python on Windows](https://docs.python.org/2.7/using/windows.html)
* **GitHub Account:** (if you plan to contribute to MTGS or fork it on GitHub).

## Obtaining MTGS

See the [GitHub Help on Cloning a Repository](https://help.github.com/articles/cloning-a-repository/)

## Running MTGS

TODO

## MTGS Project Site

Part of the MTGS Project is the Project Site that collects and presents the project documentation.
Every time the Project is commited to the *master* branch, GitHub feeds the project files to Jekyll to regenerate the MTGS Project Site, and serves it at [{{site.url}}]({{site.url}}).

If you plan to contribute to the project, it is **highly recommended** you configure your environment locally to be able and run the project through Jekyll and serve the results. This is particularly important if you're modifying the documentation of the project.

To set up a local Jekyll environment, depending on your OS:

* [Jekyll Docs for Installation on MacOS](https://jekyllrb.com/docs/installation/)
* [Jekyll Docs for Installation on Windows](https://jekyllrb.com/docs/windows/)

With all parts in place, you should be able to build and serve your local copy of the MTGS Project Site by:

```shell
$> cd <path/to>/your-mtgs-local-repo
$> bundle exec jekyll serve
   [...]
   Server address: http://127.0.0.1:4000/
   Server running... press ctrl-c to stop.
```

And navigate to `http://localhost:4000` with your web browser to see the results.



