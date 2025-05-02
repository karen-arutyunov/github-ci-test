# github-ci-test - An executable

The `github-ci-test` executable is a <SUMMARY-OF-FUNCTIONALITY>.

Note that the `github-ci-test` executable in this package provides `build2` metadata.


## Usage

To start using `github-ci-test` in your project, add the following build-time
`depends` value to your `manifest`, adjusting the version constraint as
appropriate:

```
depends: * github-ci-test ^<VERSION>
```

Then import the executable in your `buildfile`:

```
import! [metadata] <TARGET> = github-ci-test%exe{<TARGET>}
```


## Importable targets

This package provides the following importable targets:

```
exe{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.github_ci_test.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
