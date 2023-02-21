# My helix config

## Usage

```sh
cd ~/.config
git clone git@github.com/widcardw/helix-config helix
```

## Theme

I have implemented vitesse theme that inspired by antfu.

## Language Servers

Before you start to use this config, you should install the language servers globally.

#### JS/TS/JSX/TSX

```sh
pnpm add -g typescript typescript-language-server
```

Check if the language server is avaliable.

```sh
hx --health typescript
```

> ***Warning*** This config does not support eslint or prettier now.

#### rust

```sh
rustup component add rust-analyzer
```

```sh
hx --health rust
```
