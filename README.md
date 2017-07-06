# Okasaki

[![hex.pm version](https://img.shields.io/hexpm/v/okasaki.svg)](https://hex.pm/packages/okasaki)
[![Build Status](https://travis-ci.org/Qqwy/elixir_okasaki.svg?branch=master)](https://travis-ci.org/Qqwy/elixir_okasaki)

Well-structured Queues for Elixir, offering a common interface with multiple implementations with varying performance guarantees that can be switched in your configuration.


## Changelog

- 0.3.0 Backwards-compatible: Adding `empty?/1` method.
- 0.2.0 Major changes to public interface naming, adding Extractable and Insertable protocol implementations.
- 0.1.0 First release.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `okasaki` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:okasaki, "~> 0.3.0"}]
end
```

Documentation can be found at [https://hexdocs.pm/okasaki](https://hexdocs.pm/okasaki).

