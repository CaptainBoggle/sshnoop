A rewrite of [SSHPry](https://github.com/nopernik/SSHPry) in Rust.

Written by [Felix Montanari](https://github.com/CaptainBoggle) and [George Muscat](https://github.com/GeorgeMuscat)

## Build
```
git clone https://github.com/CaptainBoggle/sshnoop.git
cd sshnoop
cargo build --release
```

## Runtime Dependencies

- `strace`

## Usage

```
sshnoop <--pid <PID>|--auto|--list>

  -p, --pid <PID>  PID of the sshd pts process you want to sshnoop on
  -a, --auto       Automatically attach to the most recently created sshd pts process
  -l, --list       List all sshd pts processes you can attach to
  -h, --help       Print help
```
