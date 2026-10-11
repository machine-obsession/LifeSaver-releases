# LifeSaver

[English](#english) · [中文](#中文) · [日本語](#日本語)

## English

LifeSaver is a free Windows app that backs up your game saves. Launch a game from LifeSaver and it backs up your saves when you quit. If a save gets overwritten, or you want to go back and replay a part, you pick an earlier backup and restore it.

It's mainly for games that public save databases don't cover well: visual novels, RPG Maker games, fan translations and small indie games. Big Steam titles work too.

**Status:** LifeSaver is in a small closed alpha. There's no public download yet. When there is, the installer will be posted under [Releases](https://github.com/machine-obsession/LifeSaver-releases/releases) in this repository. This repository is also where the app checks for updates.

What it does:

- Add games by dragging a game folder into the window, scanning a folder, or importing your Steam library. It recognizes RPG Maker (2000 to MZ), Ren'Py, Wolf RPG, KiriKiri, NW.js, Unity, Unreal, GameMaker, Godot and HSP.
- Backs up when you quit a game you launched from LifeSaver. You can also set a hotkey to back up while you're still playing.
- Restores any earlier backup. Before restoring, it backs up what's on disk first, so a wrong click can be undone. If you go back and keep playing, the new progress becomes a separate branch and the old one stays.
- Each game in the list is marked with a color that tells you how it knows where the saves are. If it can't find the saves, it stops backing that game up and tells you, instead of showing it as backed up.
- The interface is in Chinese, English and Japanese.

**Feedback:** open an [issue](https://github.com/machine-obsession/LifeSaver-releases/issues). Bug reports, games whose saves weren't detected (please include the game name and the folder the saves are in), questions and requests to try the alpha are all welcome. Issues here are public.

**Cost:** free. No subscription, no ads, nothing to unlock. If you'd like to leave a tip, you can do it on [Ko-fi](https://ko-fi.com/machineobsession) or [Afdian 爱发电](https://afdian.com/a/machineobsession) (WeChat Pay / Alipay). Both pages are under Machine Obsession, the name I use online. Tips don't unlock anything; the app is the same for everyone.

The source code is in a private repository. This one only holds releases.

## 中文

LifeSaver 是一个免费的 Windows 游戏存档备份工具。从 LifeSaver 启动游戏，退出时它会自动备份一次。存档被覆盖了，或者想回到前面重玩一段，挑以前那次备份还原就行。

主要照顾公共存档数据库里常常查不到的游戏：Galgame、RPG Maker 游戏、汉化版、中文独立游戏。Steam 上的大作也能用。

**现状：** 小范围内测中，还没开放公开下载。开放以后，安装包会放在本仓库的 [Releases](https://github.com/machine-obsession/LifeSaver-releases/releases) 里，软件的自动更新也从这里取。

- 加游戏：把游戏文件夹拖进窗口、扫描一个文件夹，或者导入 Steam 库。能自动认出 RPG Maker（2000 到 MZ）、Ren'Py、Wolf RPG、吉里吉里、NW.js、Unity、Unreal、GameMaker、Godot、HSP。
- 从 LifeSaver 启动的游戏，退出时自动备份；也可以设一个快捷键，游戏开着时随手备一份。
- 以前的每次备份都能还原。还原前会先把盘上现在的存档备一份，点错了能退回。从旧存档接着玩，新进度会另开一支，原来那支还在。
- 列表里每个游戏都用颜色标出它是怎么找到存档的。找不到存档的游戏会停止备份并告诉你，不会显示成已备份。
- 界面有中文、English、日本語。

**反馈：** 在这里开 [issue](https://github.com/machine-obsession/LifeSaver-releases/issues)。报 bug、某个游戏的存档没认出来（请写上游戏名和存档所在的文件夹）、提问、想参加内测都可以。这里的 issue 是公开的。

**费用：** 免费，没有订阅、广告，也没有付费功能。想打赏的话，可以去[爱发电](https://afdian.com/a/machineobsession)（微信 / 支付宝）或 [Ko-fi](https://ko-fi.com/machineobsession)。两边的名字都是 Machine Obsession，这是我平时用的名号。打赏不解锁任何功能，软件对所有人都一样。

源码在私有仓库，这个仓库只放发布包。

## 日本語

LifeSaver は Windows 用の無料のセーブデータ自動バックアップツールです。LifeSaver からゲームを起動すると、終了時にセーブを自動でバックアップします。セーブをうっかり上書きしたときや、少し前からやり直したいときは、そのころのバックアップを選んで復元できます。

公開のセーブデータベースに載っていないことが多いゲーム、たとえばノベルゲーム、RPGツクール製のゲーム、有志翻訳版、インディーゲームを主な対象にしています。Steam の大作にも使えます。

**現在の状況：** 少人数でテスト中で、一般向けのダウンロードはまだありません。公開したら、このリポジトリの [Releases](https://github.com/machine-obsession/LifeSaver-releases/releases) にインストーラーを置きます。アプリの自動更新もここを参照します。

- ゲームの追加：フォルダーをウィンドウにドラッグする、フォルダーをまとめてスキャンする、Steam ライブラリから取り込む、のいずれかでできます。RPGツクール（2000～MZ）、Ren'Py、WOLF RPGエディター、吉里吉里、NW.js、Unity、Unreal Engine、GameMaker、Godot、HSP を自動で判別します。
- LifeSaver から起動したゲームは終了時に自動でバックアップします。ホットキーを設定すれば、遊んでいる途中でもバックアップできます。
- 過去のどのバックアップも復元できます。復元の前に今のセーブを自動でバックアップするので、間違えても戻せます。古いセーブから続けて遊ぶと新しい分岐になり、元の分岐も残ります。
- 一覧の各ゲームには、セーブの場所をどう判断したかを示す色が付きます。セーブが見つからないゲームはバックアップを止めてそのことを知らせ、バックアップ済みとは表示しません。
- 表示言語は中国語・英語・日本語から選べます。

**フィードバック：** こちらで [issue](https://github.com/machine-obsession/LifeSaver-releases/issues) を立ててください。不具合、セーブが認識されなかったゲーム（ゲーム名とセーブのあるフォルダーを書いてください）、質問、テストへの参加希望など、何でも歓迎です。issue は公開されます。

**料金：** 無料です。月額課金も広告もなく、有料の機能もありません。投げ銭は [Ko-fi](https://ko-fi.com/machineobsession) か [爱发电](https://afdian.com/a/machineobsession)（WeChat Pay・Alipay）からどうぞ。どちらのページも、ふだん使っている Machine Obsession という名前になっています。投げ銭で機能が増えることはなく、誰でも同じものを使えます。

ソースコードは非公開のリポジトリにあります。このリポジトリにはリリースだけを置いています。
