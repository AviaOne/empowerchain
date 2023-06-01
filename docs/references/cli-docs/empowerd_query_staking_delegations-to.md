## empowerd query staking delegations-to

Query all delegations made to one validator

### Synopsis

Query delegations on an individual validator.

Example:
```bash
$ empowerd query staking delegations-to cosmosvaloper1gghjut3ccd8ay0zduzj64hwre2fxs9ldmqhffj
```

```
empowerd query staking delegations-to [validator-addr] [flags]
```

### Options

```
      --count-total        count total number of records in validator delegations to query for
      --grpc-addr string   the gRPC endpoint to use for this chain
      --grpc-insecure      allow gRPC over insecure channels, if not TLS the server must use TLS
      --height int         Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help               help for delegations-to
      --limit uint         pagination limit of validator delegations to query for (default 100)
      --node string        \<host\>:\<port\> to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
      --offset uint        pagination offset of validator delegations to query for
  -o, --output string      Output format (text|json) (default "text")
      --page uint          pagination page of validator delegations to query for. This sets offset to a multiple of limit (default 1)
      --page-key string    pagination page-key of validator delegations to query for
      --reverse            results are sorted in descending order
```

### SEE ALSO

* [empowerd query staking](empowerd_query_staking.md)	 - Querying commands for the staking module
