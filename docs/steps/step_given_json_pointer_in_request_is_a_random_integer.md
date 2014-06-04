
Given JSON Pointer "{path}" in request is a random integer
=============================================================================================================

Usage example
-------------

```
Feature: zatoapi-test docs

Scenario: Given JSON Pointer "{path}" in request is a random integer

    Given address "http://apitest-demo.zato.io"
    Given HTTP method "POST"
    Given URL path "/demo/json"
    Given JSON Pointer "/a" in request is a random integer

    When the URL is invoked

    Then status is "200"
```

Discussion
----------

(None)