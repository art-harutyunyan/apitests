# GuardRails APIs

This is the repository with integration tests on the following scenarios:
==========================================================================
1) Sign in the user, add 1 item to the basket, verify that 1 item is in the basket
2) Same as previous scenario but add 2 items instead of 1 to the basket
3) Same as previous scenario but delete 1 item and validate that only 1 item remains in the basket

## Getting Started

These instructions will let you to run the tests on your machine

### Prerequisites

`npm` should be installed.
`node` v16.10.0 should be installed
`newman` should be installed. You can do this simply running `npm install -g newman`

### Installing and Running

There are 2 ways to run the tests:

Option 1:

- clone the repository
- run `newman run postman_collection.json`

Option 2:

- simply run `newman run https://www.getpostman.com/collections/0162c448641fb760e6b4`

In case you want to check the collection, please follow the [link](https://www.postman.com/art-harutyunyan/workspace/guardrailsworkspace/collection/24400532-5f09b408-94c8-4bf6-bcbf-4129ddd5ea66?action=share&creator=24400532)

