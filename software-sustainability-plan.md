Software Sustainability Plan
============================

This document outlines the Netherlands eScience Center's recommendations
regarding the creation of FAIR and sustainable software within the context of
its projects.

Through the software developed within its projects, the Netherlands eScience
Center aims to achieve maximum impact, in the broadest sense of the word. From
this, it follows that re-use by others must not only be facilitated, but even
encouraged, such that the code that is developed within the project has a good
chance to live on past the project's end date.

Naturally, there is a cost-benefit tradeoff to be made: not every piece of
software is expected to be re-used, regardless of whether it complies with
recommendations regarding the creation of FAIR and sustainable software.

Furthermore, engineers from the Netherlands eScience Center can help implement
the recommendations herein during the course of the project.

The recommendations are classified into three groups: "minimum effort",
"recommended practices", and "long term aspects". Each group is covered in more
detail below.

Minimum effort
--------------

1. From the start of the project,
    1. the software should be available under a permissive license such as
      [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html) (preferred),
      [MIT](https://spdx.org/licenses/MIT.html), or
      [BSD](https://spdx.org/licenses/BSD-3-Clause.html).
    1. the software should be developed in a publicly accessible repository such
      as [GitHub](https://github.com/) (preferred),
      [GitLab](https://about.gitlab.com/), or
      [BitBucket](https://bitbucket.org).
    1. use domain relevant open community standards, protocols, and file formats.
    1. cite software like you would cite a paper.
1. As soon as possible after the project starts,
    1. add a persistent identifier to the software. There are many flavors of
      persistent identifier that can be used for software. We prefer to [use
      DOIs issued by Zenodo](https://guides.github.com/activities/citable-code/).
    1. include prominently published documentation that explains what problem the
      software addresses; illustrate the software's intended usage with
      examples.

Recommended practices
---------------------

1. Make sure your software is findable by search engines and humans alike:
    1. by creating an entry in software repositories such as the Research
      Software Directory (https://software.esciencecenter.nl), KBLab
      (http://lab.kb.nl/), Biotools (https://bio.tools/), etc.
    1. by putting software in package managers such as
      [PyPI](https://pypi.org/),
      [RubyGems](https://rubygems.org/),
      [maven](https://search.maven.org/), or
      [NPM](https://www.npmjs.com/) (as applicable given the language of choice)
1. Follow the best practices outlined here
  https://bestpractices.coreinfrastructure.org/en/ (more compliance is better),
  or from an equivalent list. Be transparent in the degree to which your
  software is compliant by prominently publishing the results (e.g. as a
  'badge').

Long term aspects
-----------------

Aspects to consider for after the project ends:

1. describe what support will be available for the package
1. What is the package's bus factor?
1. How many external contributors are there?
1. what funding/ in-kind contributions are available to maintain and support the package?
1. What can be done to connect to existing communities?


