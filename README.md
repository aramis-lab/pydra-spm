# pydra-spm

Pydra tasks for SPM.

[Pydra] is a dataflow engine which provides a set of lightweight abstractions
for DAG construction, manipulation, and distributed execution.

[SPM] is a software package for the construction and assessment of spatially
extended statistical processes used to test hypotheses about functional imaging
data.

This project exposes some of SPM's utilities as Pydra tasks to facilitate their
incorporation into more advanced processing workflows.

## Development

Setup for development requires [Poetry].

Install the project and its dependencies with:

```console
make install
```

Run the tests with:

```console
make test
```

Build the project's documentation with:

```console
make docs
```

Format the code before review with:

```console
make format
```

## Licensing

This project is released under the terms of the Apache License 2.0.


[Pydra]: https://nipype.github.io/pydra
[SPM]: https://www.fil.ion.ucl.ac.uk/spm
[Poetry]: https://python-poetry.org
