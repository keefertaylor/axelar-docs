## axelard query staking validator

Query a validator

### Synopsis

Query details about an individual validator.

Example:
`$ <appd> query staking validator axelarvaloper1gghjut3ccd8ay0zduzj64hwre2fxs9ldmqhffj`

```
axelard query staking validator [validator-addr] [flags]
```

### Options

```
      --height int      Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help            help for validator
      --node string     `<host>:<port>` to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
  -o, --output string   Output format (text|json) (default "text")
```

### Options inherited from parent commands

```
      --chain-id string     The network chain ID (default "axelar")
      --home string         directory for config and data (default "$HOME/.axelar")
      --log_format string   The logging format (json|plain) (default "plain")
      --log_level string    The logging level (trace|debug|info|warn|error|fatal|panic) (default "info")
      --trace               print out full stack trace on errors
```

### SEE ALSO

- [axelard query staking](/cli-docs/v0_31_2/axelard_query_staking) - Querying commands for the staking module