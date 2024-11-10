# gleave

[![Package Version](https://img.shields.io/hexpm/v/gleave)](https://hex.pm/packages/gleave)
[![Hex Docs](https://img.shields.io/badge/hex-docs-ffaff3)](https://hexdocs.pm/gleave/)

Writing a CLI program in Gleam? Wanna exit with a status code? Just `gleave`!

```gleam
import gleave

fn main() {
  // Exit with status code 123
  gleave.exit(123)
}
```

## Installation

```sh
gleam add gleave
```
