# guessing_game


My first hello world program in rust with cargo setup

following are steps

install rust from https://www.rust-lang.org/tools/install
python install cargo
cargo new guessing_game
cargo run

got few errors:
 had a similar issue "error: linking with link.exe failed: exit code: 1"

To solve it, I did

rustup toolchain install stable-x86_64-pc-windows-gnu
then

rustup default stable-x86_64-pc-windows-gnu
and

cargo build
cargo run

<img width="452" alt="image" src="https://github.com/shilpaakula06/guessing_game/assets/70659144/18e8b22b-0245-4d69-8682-6939e145d916">
