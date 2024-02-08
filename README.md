# taskfiles
Collection of useful taskfiles for taskfile.dev

## Go
```sh
* build:               Builds an application. Use $BUILD_INFO_LDFLAGS, $APP_NAME variables
* download-deps:       Downloads go module dependencies
* fmt:                 Formats the code. Uses gofumpt,goimports,tagalign,gci
* install-lint:        Installs GolangCI linter into ./bin folder. Version can be overridden via $GOLANGCI_LINT_VERSION env variable
* lint:                Executes GolangCI linter
* test:                Executes go test
```