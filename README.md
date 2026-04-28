# worklink

招商随行（[WorkLink](https://www.cm-worklink.com)）的 Arch Linux 打包。

## 安装

```bash
git clone https://github.com/cmriat/worklink.git
cd worklink
makepkg -si
```

`makepkg` 会自动下载官方 deb 包、解出内容并安装到系统。

## 依赖

运行依赖：`desktop-file-utils` `gtk3` `hicolor-icon-theme` `libnotify` `libsecret` `libxss` `libxtst` `nss` `util-linux-libs`

可选：`libappindicator-gtk3`（系统托盘图标）

## 卸载

```bash
sudo pacman -R worklink
```
