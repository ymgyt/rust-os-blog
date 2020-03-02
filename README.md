# Writing an OS in Rust


## Usage

### Real Machine

```console
dd if=target/x86_64-blog_os/debug/bootimage-blog_os.bin of=/dev/sdX && sync
```

### Build And Run

```console
cargo xrun
```