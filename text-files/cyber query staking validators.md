Query details about all validators on a network.

Example:
$ cyber query staking validators

Usage:
  cyber query staking validators [flags]

Flags:
      --count-total       count total number of records in validators to query for
      --height int        Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help              help for validators
      --limit uint        pagination limit of validators to query for (default 100)
      --node string       <host>:<port> to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
      --offset uint       pagination offset of validators to query for
  -o, --output string     Output format (text|json) (default "text")
      --page uint         pagination page of validators to query for. This sets offset to a multiple of limit (default 1)
      --page-key string   pagination page-key of validators to query for
      --reverse           results are sorted in descending order

Global Flags:
      --chain-id string     The network chain ID
      --home string         directory for config and data (default "/Users/user/.cyber")
      --log_format string   The logging format (json|plain) (default "plain")
      --log_level string    The logging level (trace|debug|info|warn|error|fatal|panic) (default "info")
      --trace               print out full stack trace on errors