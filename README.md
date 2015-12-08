# PhoenixTodosApi

## A Todo Application written in Elixir and using Phoenix Framework
This is the backend for a simple client-server web application using Phoenix and Elixir on the server, with PostgreSQL as the store data. On the client side, the Ember Javascript framework will provide the user interface and communicate changes to the server. The Ember application's code is accessible from [here](https://github.com/daqo/elixir-ember-todo).

To start your Phoenix app:

  1. Install dependencies with `mix deps.get`
  2. Change the database username and password in dev.exs and test.exs
  2. Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  3. Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

## Runt Tests
`mix test`

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: http://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix