
Then header "{header}" is empty
=============================================================================================================

Usage example
-------------

```
Feature: zato-apitest docs

Scenario: Then header "{header}" is empty

    Given address "http://apitest-demo.zato.io"
    Given URL path "/demo/json"

    When the URL is invoked

    Then header "X-Should-Be-Empty" is empty
```

Discussion
----------

(None)