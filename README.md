# pydra-spm

![][status-docs]
![][status-test]

----

Pydra tasks for SPM.

[Pydra][pydra] is a dataflow engine
which provides a set of lightweight abstractions
for DAG construction, manipulation, and distributed execution.

[SPM][spm] is a software package
for the construction and assessment of spatially extended statistical processes
used to test hypotheses about functional imaging data.

This project exposes SPM utilities as Pydra tasks
to facilitate their incorporation into more advanced processing workflows.

## Development

This project is managed with [Hatch][hatch]:

```console
pipx install hatch
```

To run the test suite:

```console
hatch run test
```

To fix linting issues:

```console
hatch run lint:fix
```

To check the documentation:

```console
hatch run docs:serve --open-browser
```

## Licensing

This project is distributed under the terms of the [Apache License, Version 2.0][license].

[hatch]: https://hatch.pypa.io

[license]: https://opensource.org/licenses/Apache-2.0

[pydra]: https://nipype.github.io/pydra

[spm]: https://www.fil.ion.ucl.ac.uk/spm

[status-docs]: https://github.com/aramis-lab/pydra-spm/actions/workflows/docs.yaml/badge.svg

[status-test]: https://github.com/aramis-lab/pydra-spm/actions/workflows/test.yaml/badge.svg