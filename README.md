# {{name}}
[![Travis](https://img.shields.io/travis/{{github_user}}/{{name}}.svg)]()
![https://ci.appveyor.com/api/projects/status/?svg=true](https://ci.appveyor.com/api/projects/status/github/{{github_user}}/{{name}}?svg=true)

Basic template for typical components used in a Rust project. Currently is not
generated through templates but is future plan.

In particular this has:

- Continuous Integration
    - [Travis CI](.travis.yml)
    - [Appveyor](appveyor.yml)
    - [Gitlab](.gitlab-ci.yml)
- Integration test location (always forget if *test* or *tests*)

All the rest are just generated from `cargo`.
