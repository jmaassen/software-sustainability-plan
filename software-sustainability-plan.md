enable re-use by others
explain how the software developed within the project is expected to live on past the project's end date.
we want sustainable && FAIR software

Engineer will help implementing the below aspects:

Aspects to consider for the duration of the project:

- required (for FAIRness):
    - permissive license
    - public repository
    - add persistent identifier (e.g. DOI from Zenodo) to the software
    - README-like document that explains
        - what problem the software addresses
        - example usage
    - Use domain relevant community standards/ open protocols and standards and file formats
- recommended, for more FAIRness:
    - explicit criteria relating to reproducibility like seeds if your algorithm
      uses stochastic processes)
    - automatic integration between doi issuer and software version control, e.g Zenodo-GitHub integration
    - be findable by search engines and humans
        - entry in software repository like RSD, KBLab, Biotools etc
        - include software citations in papers including doi
        - put in package manager when applicable to the language of choice (PyPI, gems, maven, conda, etc.)
- recommended, for more sustainability (more compliance is better):
    - https://bestpractices.coreinfrastructure.org/en/ gold criteria

Aspects to consider after the project ends:

- describe what support will be available for the package
    - bus factor
    - external contributors
    - what funding/ in-kind contributions are available?
    - connect to an existing community when possible


