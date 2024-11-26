# funding-manifests-evolution

[dir.floss.fund](https://dir.floss.fund/) is an "open directory of FOSS projects
looking for funding and financial assistance". Projects seeking funding can
provide a [funding.json](https://floss.fund/funding-manifest/) manifest as a
signalling mechanism.

dir.floss.fund crawls the manifests, and maintains an up-to-date internal
database ([portal source](https://github.com/floss-fund/portal)). It also
provides a [daily dump of its database of manifests](https://dir.floss.fund/browse/export).

This repository tracks the history of funding-manifest databases. This data
is maintained to aid analysis of the impact of the FLOSS fund.

The tools that update this repository are part of the
[floss-funding-envelope](https://github.com/shreekumar3d/floss-funding-envelope)
project; it also generates reports from this data.

# LICENSE

Everything in this repository is licensed under the same license as the listing
content in dir.floss.fund :
[CC BY-SA 4.0](https://creativecommons.org/licenses/by/4.0/deed.en)
