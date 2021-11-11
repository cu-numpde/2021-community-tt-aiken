# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: libCEED

libCEED is an API that is part of the Exascale Computing Project, run by the U.S. Department of Energy, that is meant to help computational scientists take advantage of next-generation, massively parallel, heterogeneous computing architectures. The goal of the API is to allow the average user to concern themselves only with the low-level algebraic manipulations required for their specific application. Users can then choose from a variety of backends to use for running their application on CPUs or GPUs. The API is capable of handling a variety of finite element implementations and currently has a handful of implementations for various problems in computational physics, including solid and fluid mechanics. 

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL | https://github.com/CEED/libCEED |
| Main/documentation website | https://libceed.readthedocs.io/en/latest/ |
| Year project was started | Sept. 2017 |
| Number of contributors in the past year | 18 |
| Number of contributors in the lifetime of the project | 29 |
| Number of distinct affiliations | 5-10 |
| Where do development discussions take place? | GitHub issues  |
| Typical number of emails/comments per week? | 13 (past week) |
| Typical number of commits per week? | 25 |
| Typical commit size | less than 50 insertions/deletions |
| How does the project accept contributions? | pull requests |
| Does the project have an automated test suite? | yes |
| Does the project use continuous integration? | yes |
| Are any legal/licensing steps required to contribute? | no |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [x] I have installed the software
- [x] I have run at least one example
- [x] I have run the test suite
- [x] The test suite passes

### Notes/concerns/risks

When I built 'navierstokes.c', I got a bunch of '-Wtypedef-redefinition' errors that didn't impact the testcase that I ran but might need fixing. Leila Ghafarri also opened an issue in April about the SU/SUPG stabilization methods being broken in the current 'density_current' problem. I'm hoping this is a problem with the 'density_current' problem and not with 'navierstokes.c', or else it might impact my project. Otherwise, I see no significant risks to completing a project with the navierstokes solver in libCEED.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
