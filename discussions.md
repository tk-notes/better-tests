* Setup bem claro e explicito.
  * Dentro do contexto.
  * Exemplo: `spec/models/content/live_spec.rb`
  * Problema recorrente? Duplicação de código. Achar o balanço entre a duplicação e o desacoplamento.


- Testar o que realmente deve ser testado.
  * Pensar em casos de uso: context
  * Exemplo: `spec/models/content/live_spec.rb`


* Para endpoints da APIs.
  * Desacoplamento de actions.
  * Exemplo: `spec/api/v11/hosts/volunteer_positions/*`

--------

[Debating about (S)etup > (E)xercise > (V)erify > (T)ear-down](https://github.com/Worldpackers/worldpackersplatform/pull/2391)

[Better Exercise](https://github.com/Worldpackers/worldpackersplatform/pull/2420)

[Decoupling controller actions specs](https://github.com/Worldpackers/worldpackersplatform/pull/2392)
