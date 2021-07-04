# API Best Practices

1. What does REST stand for?

Representational State Transfer

1. REST APIs are designed around a ____.

resources

1. What is an identifer of a resource? Give an example.

* https://patrick.mil/is/awesome
* https://patrick.mil/is/great
* https://patrick.mil/is/handsome

- i can go all day.

1. What are the most common HTTP verbs?

get, post, put, delete and patch.

1. What should the URIs be based on?

should have nouns stating the resource, not verbs.

1. Give an example of a good URI.

https://where2gonow.xyz/about

1. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

When API's have a lot of small resources, the client has to send a bunch request to get all the info they need from it. i wouldnt want to do that, so it must be a bad thing.

1. What status code does a successful GET request return?

status code 200.

1. What status code does an unsuccessful GET request return?

status code 404.

1. What status code does a successful POST request return?

status code 201.

1. What status code does a successful DELETE request return?

status code 204.


[Back to Main Page](../README.md)