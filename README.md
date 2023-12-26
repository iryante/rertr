Install Dependencies
```rust
sudo apt update && sudo apt install libfuse2
```
Install Owshen
```rust
wget -O owshen https://github.com/OwshenNetwork/owshen/releases/download/v0.1.0/Owshen_v0.1.0_x86_64.AppImage; chmod +x owshen
mv owshen /usr/local/bin 
owshen --version
```

Init Wallet
```rust
owshen init
```

Simpan Mnemonic Pharse!!!
Cek Wallet Address
```rust
owshen info
```

Cek web wallet (Optional)
Jalankan ini
```rust
owshen wallet
```

Lalu buka http://YOURIP:9000
