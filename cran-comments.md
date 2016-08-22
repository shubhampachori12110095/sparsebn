## Test environments
* local OS X install, R 3.3.1
* ubuntu 12.04 (travis-ci), R 3.3.1
* win-builder (devel and release)

## R CMD check results
There were no ERRORs or WARNINGs.

There was 1 NOTE:

* checking CRAN incoming feasibility ... NOTE
Maintainer: ‘Bryon Aragam <sparsebn@gmail.com>’

New submission

This is the first version of this package that has been submitted to CRAN.

## Re-submission notes
- I get

Reading CITATION file fails with
  $ operator is invalid for atomic vectors
when package is not installed.

Fixed by replacing packageDecription with meta as described in Section 1.9 of R-exts.

## Dependencies

CHECK has been run on all dependencies and passed.

## Reverse dependencies

This is a new release, so there are no reverse dependencies.