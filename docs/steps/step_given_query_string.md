
Given query string "{query_string}"
=============================================================================================================

Usage example
-------------

```
Feature: zatoapi-test docs

Scenario: Given HTTP method "{method}"

    Given address "http://apitest-demo.zato.io"
    Given HTTP method "POST"
    Given URL path "/demo/json"
    Given query string "?a=1&b=2"
    Given format "JSON"

    When the URL is invoked

    Then status is "200"
```

Discussion
----------

(None)