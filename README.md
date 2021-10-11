# Rime Input Method Engine

First of all, I love Rime.

Here is a wubi table I modified from jidian-wubi.

## Install Rime for IBus

```
sudo apt install ibus-rime
```

## Install Rime for Fcitx

```
sudo apt install fcitx-rime
```

## Configure Rime

```
cp *.yaml ~/.config/ibus/rime/

cp *.yaml ~/.config/fcitx/rime/
```

## Restart IBus Rime

```
ibus-daemon -xdr
```

## Rime on MacOS

```
brew cask install squirrel

git clone https://github.com/rime/rime-pinyin-simp
git clone https://github.com/rime/rime-wubi

cp -r *.yaml ~/Library/Rime/
```

Avoid period with double-space: `System -> Keyboard -> Text -> unselect Add period with double-space`

## Rime on Windows

```
cp *.yaml /mnt/c/Users/zhiwei/AppData/Roaming/Rime/
```

## References

Clover Pinyin: https://github.com/fkxxyz/rime-cloverpinyin
