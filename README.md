# API Testing QA — 15 Days of Postman for Testers

My completed collections from Postman's **15 Days of Postman – for Testers** challenge. Each day covers one API testing topic, and the collections are exported here so the requests, scripts, and tests can be imported and reviewed.

## Topics covered

| Day | Topic | What I practiced |
| :-- | :-- | :-- |
| 01 | API client | Sending requests, reading responses |
| 02 | Version control | Forking and merging collections |
| 03 | Debugging | Postman Console, inspecting requests |
| 04 | Authorization | Auth types and auth inheritance across a collection |
| 05 | Variables and scripts | Collection variables, pre-request and test scripts |
| 06 | API tests | Writing `pm.test` assertions on status, body, and headers |
| 07 | Run test suites | Running collections with the Collection Runner |
| 08 | Output test results | Reporting and reviewing run results |
| 09 | API workflows | Controlling request order with `postman.setNextRequest` |
| 10 | Test coverage | Covering positive and negative cases |
| 11 | Validation | JSON schema validation of responses |
| 12 | Use libraries | Using built-in libraries in scripts |
| 13 | Mock servers | Creating and calling mock servers |
| 14 | More tests | Additional assertions and edge cases |
| 15 | Submit for badge | Final submission |

## How to use

1. Open Postman → **Import** → select one or more `Day XX - ....postman_collection.json` files.
2. Open the collection and check the **Pre-request Script** and **Tests** tabs to see the scripts.
3. Run a collection with the **Collection Runner**, or from the command line with Newman:

```bash
npm install -g newman
newman run "Day 06- API tests.postman_collection.json"
```

Note: each collection contains a "Submit your solution" request that was used by the challenge to check the answers.
