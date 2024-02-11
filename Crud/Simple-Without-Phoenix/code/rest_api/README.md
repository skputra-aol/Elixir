# RestApi

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `rest_api` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:rest_api, "~> 0.1.0"}
  ]
end
```

#FOLDER STRUCTURES :

├── README.md
├── .formatter.exs  (Used by mix to format your elixir files)
├── .gitignore  (A default gitignore file with all temporary files ignored)
├── mix.exs  (Mix project definition file. Similar to package.json in Node.js)
├── lib/
│   ├── rest_api.ex  (File defining the root Module for our application)
│   └── rest_api/application.ex (File defining a OTP Application with supervisor)
└── test/
    ├── test_helper.exs  (File to write our test helpers)
    └── rest_api_test.exs (File to test our application)




The MixProject has two public functions:

project: It returns the project configuration like the project name, version, elixir version to use, etc.
application: It is the entry point to our application.
and one private function:

deps: It returns a list of dependencies of this project.




Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/rest_api>.

