# dhall

Scoop bucket for [Dhall](https://github.com/dhall-lang/dhall-haskell) binaries.

To add the bucket to your Scoop configuration, run the following command in your terminal:

```bash
scoop bucket add dhall https://github.com/sambeckingham/dhall
```

## Included Binaries

| Binary | Description | Shims |
|--------|-------------|-------|
| [dhall-json](https://github.com/dhall-lang/dhall-haskell/tree/master/dhall-json) | Provides a Dhall to JSON, a JSON to Dhall and a derivative Dhall to YAML compiler.  Note the YAML compiler is lesser featured than the one in the `dhall-yaml` package. | `dhall-to-json`, `json-to-dhall`, `dhall-to-yaml`|
| [dhall-bash](https://github.com/dhall-lang/dhall-haskell/tree/master/dhall-bash) | Provides a Dhall to Bash compiler. Does not compile all Dhall syntax to Bash. | `dhall-to-bash`|