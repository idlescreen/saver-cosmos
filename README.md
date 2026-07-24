# saver-cosmos

Official **cosmos** visualizer plugin for [IdleScreen](https://github.com/idlescreen/idle).

## Build

Requires the idle engine checked out into `./idle` for `idle-api` path deps:

```bash
git clone https://github.com/idlescreen/idle-saver-cosmos.git
cd idle-saver-cosmos
git clone https://github.com/idlescreen/idle.git idle
cargo build --release
```

## Install

After adding the IdleScreen package repository:

```bash
sudo apt install idle-saver-cosmos
# or: sudo dnf install idle-saver-cosmos
```

See [idlescreen.github.io/packages](https://idlescreen.github.io/packages/).

## License

Apache-2.0. See [LICENSE](LICENSE).
