# genpasswd

simple password generator written in C, originally made by [lilyyllyyllyly](https://github.com/lilyyllyyllyly), turned into a cryptographically secure password generator by me ([unixpup](https://github.com/unixpup))

# Installation

## Dependencies

- x86_64v3 (Modify the Makefile in case you want to define your architecture explicitly.
- Clang >=19 (Needed for ThinLTO and CFI)
- libsodium
- ncurses

```
git clone https://github.com/unixpup/genpasswd
cd genpasswd
make
```

you probably want to put it in your PATH (somewhere like `~/.local/bin/genpasswd` should be fine, if that directory is in your `PATH`!)

# Usage

Simply execute `./genpasswd`

## Example

```
genpasswd
Cryptographic engine started successfully!
Result scrambled for password usage (Base64): cctjfoj6nwl68iljb0mvkPdeKCjtLieExoMWeowtn0BVP--GQ8EdKvcieDBI_ZvI1uMvJRpkctgnUZswnn9YiQ==
```
