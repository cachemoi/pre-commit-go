# Set of pre-commit hooks for go projects

This is a set of [pre-commit]("https://pre-commit.com/") hooks for go projects,
based on and inspired by [this set]("https://github.com/domodwyer/pre-commit") and [this one]("https://github.com/dnephin/pre-commit-golang")

List of hooks:

* `go-golangci-lint`: Run golangci-lint
* `go-test`: Run all tests in the repository
* `go-goimports`: Runs `goimports` on changed files
* `go-mod-tidy`: Runs `go mod tidy -v`
* `go-mod-vendor`: Runs `go mod vendor`
