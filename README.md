Erlang demo project with Elixir dependencies.

Why?
In an Elixir project Erlang is a first-class citizen. 
It's easy to add a dependency to an existing erlang project and it just works.

It would be nice to have the same experince in an erlang project.

As it is right now, it's easier to migrate an existing erlang project to an elixir project
in order to be able to mix erlang and elixir code .. than including the elixir dependencies.

Goals:
 - include elixir dependencies with rebar_mix
 - create a release with all the vm included with relx 
 - combine logs from elixir and erlang in the same log file
 - combine metrics
 - create simple wrapper 'erlang style' for elixir modules
 - multiline-like support in erlang
 - editor mode - emacs - to cross reference erlang and elixir code
 - easy to trace both erlang and elixr modules
 - remote console iex/erl for testing both erlang end elixir code
