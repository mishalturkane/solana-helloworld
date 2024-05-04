*Problem i*

root@PAVILION:~/hello_world2# rustc --version
rustc 1.78.0 (9b00956e5 2024-04-29)
root@PAVILION:~/hello_world2# solana --version
solana-cli 1.17.25 (src:d0ed878d; feat:3580551090, client:SolanaLabs)
root@PAVILION:~/hello_world2# cargo build-bpf
error: package `toml_edit v0.21.1` cannot be built because it requires rustc 1.69 or newer, while the currently active rustc version is 1.68.0-dev
Either upgrade to rustc 1.69 or newer, or use
cargo update -p toml_edit@0.21.1 --precise ver
where `ver` is the latest version of `toml_edit` supporting rustc 1.68.0-dev
root@PAVILION:~/hello_world2# 
