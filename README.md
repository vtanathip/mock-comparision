# Mock Comparision
The general idea when we're working with a Mock server we need to consider three things which are
- Is it support the protocols that you're going to test?
- Is it follow the Test Double concept?
- Is it able to handle a lot of requests?

## Test Double (quick version)
- Mock : are pre-programmed with expectations which form a specification of the calls they are expected to receive (Behavior)
- Stub : provide canned answers to calls made during the test, usually not responding at all to anything outside what's programmed in for the test. (State)

## References
- [Comparision Table](https://trafficparrot.com/Service_virtualization_and_stubbing_tools_comparison.html)
- [Mock Performance](https://developers.ascendcorp.com/%E0%B8%A1%E0%B8%B2%E0%B8%94%E0%B8%B9-performance-%E0%B8%82%E0%B8%AD%E0%B8%87-node-red-vs-wiremock-vs-karate-vs-mountebank-%E0%B8%81%E0%B8%B1%E0%B8%99-ecbce5ceb90)
- [Example mountebank](https://medium.com/digio-australia/mock-it-with-mountebank-88762dadac1f#:~:text=using%20.js%20file-,What%20is%20Mountebank%3F,proxy%20to%20the%20real%20service.)
- [Test Double](https://martinfowler.com/bliki/TestDouble.html)
- [The Rick and Morty API](https://rickandmortyapi.com/) for mock and stub in mock server
