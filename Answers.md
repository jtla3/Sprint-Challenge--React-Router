##Answers
* 1. What is the difference between _server side routing_ and _client side routing_?

* The difference is where the `DOM` gets `rendered`. In client side routing ther route is handled internally through `JavaScript`.

* 2. Mention some advantages of using client side routing.

* Some advantages of using client side routing is it's faster routing between views because less data is processed.

* Smoother transitions and animation between views is easier to implement.

* 3. Which component is used to define a route and what _props_ are commonly added to it?

* The Route component and it will take in two properties (path and component)

* 4. How can I make sure that the component associated with the _"/"_ route is not displayed for every other route?

* Add `exact` to route component.