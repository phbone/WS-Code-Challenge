Rebalancing Module
===================

Simple Portfolio Rebalancing Module.

To view the given run case:

 1) Open index.html
 
 2) Right Click, "Inspect Element"
 
 3) Click "Console" Tab to see logged results


Technical Choices
----------

Javascript

    - Easy way to solve the challenge and run unit tests without having to set up an environment.
    - Future Improvement: This module would be more useful in a WS backend language such as Java or Ruby.

Input portfolio as list of Asset objects

    - If using Django, data models will most likely come in form of objects.

More Tests

    - Write more tests to check that suggested buys never exceed target weight
    - Similarly, check that suggested sells are never lower than target weight
    - Check that there is no missing information in portfolio

More Robust

    - Include rebalancing transaction costs in the module
    - If transaction costs are significant, apply thresholds before rebalancing


Testing
-----

Running Unit Tests

1) This module uses Jasmine(http://jasmine.github.io/), which runs off Karma(http://karma-runner.github.io/0.12/index.html).

2) Alternatively, copy lib/tests.js into fiddle(http://jsfiddle.net/openspectrum/wzAyL/) and "Run"
