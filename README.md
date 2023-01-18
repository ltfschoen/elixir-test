# Setup

* macOS

  * Install Elixir - https://elixir-lang.org/install.html

```
brew install elixir;
elixir --version
```

  * Running Elixir - https://elixir-lang.org/getting-started/introduction.html

    * Interactive Elixir (REPL) 
      ```
      iex
      ```

    * Elixir Scripts
      ```
      elixir src/001_helloworld.exs;
      ```

# References

* Elixir
  * Elixir/Erlang Syntax Crash Course - https://elixir-lang.org/crash-course.html
  * Phoenix Web App Framework (MVC) in Elixir - https://hexdocs.pm/phoenix/overview.html
    * [Ecto](https://hexdocs.pm/ecto/Ecto.html) (i.e. schema, queries. similar to Ruby on Rails ActiveRecord)
    * [Plugs](https://hexdocs.pm/plug/readme.html) (adapters for web server including routing, requests methods/logging/parsing, sessions, ssl)
    * Cowboy (web server in Erlang provided as an adapter by Plug)
  * Nerves - https://hexdocs.pm/nerves/getting-started.html
    * Build and deploy Nerves firmware bundle (embedded systems) containing a minimal Linux platform and Elixir app. Nerve fetches the system and toolchain from the cloud upon compilation of the bundle dependencies
  * Learn Elixir with [DockYard Academy](https://github.com/DockYard-Academy)
  * [ASDF VM](https://asdf-vm.com/) for Multiple Runtime Version Control (i.e. combines NVM, PyEnv, RBEnv, etc)
  * [Livebook.dev](https://livebook.dev/) for interactive notebooks for Elixir (similar to Python's Jupiter Notebooks)
  * [Dev Containers](https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/adding-a-dev-container-configuration/introduction-to-dev-containers) on Github
