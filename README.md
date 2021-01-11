# Rime Input Method Engine

First of all, I love Rime.

Here is a wubi table I modified from jidian-wubi.

## Install Rime for IBus

```
$ sudo apt install ibus-rime librime-data-pinyin-simp
```

## Configure Rime

```
$ cp *.yaml ~/.config/ibus/rime
```

## Restart Rime

```
$ rm -f ~/.config/ibus/rime/default.yaml
$ ibus-daemon -xdr
```

## Rime on MacOS

```
brew cask install squirrel

git clone https://github.com/rime/rime-pinyin-simp
git clone https://github.com/rime/rime-wubi

cp -r *.yaml ~/Library/Rime/
```

Avoid period with double-space: `System -> Keyboard -> Text -> unselect Add period with double-space`
