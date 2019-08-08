## Test environments
* local ubuntu 18.04 install, R 3.5.3, R 3.6.0
* ubuntu 14.04 (on travis-ci), R-devel, R 3.6.0, R 3.5.3
* macOS 10.13 (on travis-ci), R 3.6.1
* windows server 2012 R2 (on AppVeyor), R 3.6.1
* win-builder, R-devel, R 3.6.1

## R CMD check results

0 errors | 0 warnings | 1 note

* This is a new release.
* Package suggested but not available for checking: 'fable' (included in Additional_repositories and also awaiting CRAN acceptance).

## Re-submission

* Fixed URL in vignette.
* Updated tests and examples to conditionally depend on fable.
