* Clear and explicit setup:
  * Inside a context block.
  * Example: `spec/models/content/live_spec.rb`
  * What is the problem here? Code duplication. We need to find the balance between duplication and uncoupled code.

- Test (only) what need to be tested:
  * Think about "use cases": context block helps in this case.
  * Example: `spec/models/content/live_spec.rb`

* For APIs endpoints:
  * Decoupling controllers actions.
  * Example: `spec/api/v11/hosts/volunteer_positions/*`

--------

[Debating about (S)etup > (E)xercise > (V)erify > (T)ear-down](https://github.com/Worldpackers/worldpackersplatform/pull/2391)

[Better Exercise](https://github.com/Worldpackers/worldpackersplatform/pull/2420)

[Decoupling controller actions specs](https://github.com/Worldpackers/worldpackersplatform/pull/2392)
