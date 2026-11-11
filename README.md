# // jjozzietech

Enterprise lab. Sydney rack. au-syd region.

I run an Akash Network GPU compute provider on a 23-node Kubernetes cluster
and write about what actually breaks.

## // current focus

- Akash provider operations at production scale
- Platform architecture — Proxmox, Kubernetes HA, Ceph, GPU passthrough
- Anti-mining defense for permissionless compute providers
- DePIN infrastructure economics

## // validators

Multi-chain Cosmos validator **jjozzietech**, run from the same Sydney rack.

- **Kava** (`kava_2222-10`): active. [validator page](https://jjozzietech.com.au/validators/kava/)
- **Akash** (`akashnet-2`): active. The chain has approved a move to Solana (AEP-79); timing is not yet finalised. [validator page](https://jjozzietech.com.au/validators/akash/)

How it is run:

- Horcrux 2-of-3 threshold signing, with a hot standby on a separate host for each chain
- Prometheus/Grafana monitoring and a public incident log on the validator pages
- Governance: votes and the reasoning behind them published on the validator pages
- Public Kava RPC, REST, gRPC and daily snapshots with sha256: `rpc.jjozzietech.com.au:9443`, gRPC `:9444`, [snapshots](https://snapshots.jjozzietech.com.au:9443/kava/)
- Identity: Keybase `C0BB391968FE28AE` · security contact `security@jjozzietech.com.au`

## // around the web

- Website — [jjozzietech.com.au](https://jjozzietech.com.au) (log, stack) · [validators](https://jjozzietech.com.au/validators/kava/)
- Akash provider — `akash1sev...wd4e` (au-syd)
- X — [@jjozzietech](https://x.com/jjozzietech)
- Discord — `jjozzietech` in the Akash Network server
