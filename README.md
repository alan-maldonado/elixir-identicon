# Identicon

Generates an image 250px x 250px with a 5x5 grid of squares, each 50px tall and wide.

Start the application
```
iex -S mix
```

Create an identicon
```
iex> Identicon.main("alan")
```

Browse over the folder profiles, and look for the `png` file.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:identicon, "~> 0.1.0"}]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).
