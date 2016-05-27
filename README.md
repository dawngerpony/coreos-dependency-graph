systemd Dependency Graph Generator
==================================

Requires:

* python
* graphviz command line tools (i.e. `dot`)
* A directory containing systemd service files.

To run: `./run.bash`

Generates a `graph.dot` file and a `graph.png` visual representation of a set of [systemd][systemd] services, based on reading the
[service files][service-files].

`Requires` lines are distinct from `Wants` lines.

[systemd]: https://en.wikipedia.org/wiki/Systemd
[service-files]: https://www.freedesktop.org/software/systemd/man/systemd.service.html
