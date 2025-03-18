Get an x-token from triton RPC and edit the Vixen.toml file with the token.

This project uses yellowstone-vixen to listen for ix events directly from geyser
when a registered ix event is recorded (InitializeLBPair in this case) we can see the accounts and ix_data printed on the console

usage

```bash
cargo run -- --config Vixen.toml
```

for logs use the following command

```bash
RUST_LOG=info cargo run -- --config Vixen.toml
```
