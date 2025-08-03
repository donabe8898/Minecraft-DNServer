
# 1 FabricとMODの導入
## 1.1 Fabric
**※注意　MODローダーにForgeではなくfabricを使用しています**
- [Fabricのダウンロードはこちら](https://fabricmc.net/use/installer/)
で**Download for Windows**を選択

- インストーラーをダウンロードしアプリを起動→Minecraftバージョン **1.20.1**を選択しインストール。
- Fabric loaderバージョン: `0.15.11`

## 1.2 MOD
1. [このgoogle driveリンク](https://drive.google.com/drive/folders/1yzhj1PwvNntn8N7vom3CWsPfmvKskvFV)
に飛んでmods.zipをダウンロード→解凍

2. 中身のjarファイルを作成した起動構成のmodsディレクトリへコピー

> ## 主な導入modの紹介
> **Create mod**
>
> - みんな大好きからくり機械を作れるmod
>
> **Lightman Currency mod**
>
> - 様々なコインを使って経済活動を行うことができるmod。自動販売機、レジ、ATM、券売機、スロットマシンなどなど
>
> - [modのドキュメント(英語)](https://github-wiki-see.page/m/Lightman314/LightmansCurrency/wiki_index) 目を通しながらプレイすることをおすすめする
>
> **Simple Voice Chat**(任意)
>
> - マイクラ内で近くの人とVCができます
>
> **Hey that's mine**(サーバー側MOD)
>
> - プライベートなチェストを作成可能なmod



# 2 Tailscale

## 2.1 Tailscaleとは
- Tailscaleは安全なプライベートネットワークを簡単に構築できる、WireGuardベースのVPNサービスです（~~AIくん迫真の回答~~）
    - 要はポート解放とか何もせずにサーバーを外部に公開できる魔法のサービスです
- 何が嬉しいの? → ポートを解放しないのでセキュリティが固い,

- 参考: [分散型VPNサービスtailscaleの魅力|note](https://note.com/minimalist_meme/n/n64646ce68128)


## 2.2 インストール

1. [Tailscaleのダウンロードサイト](https://tailscale.com/download)からお使いのOSに合わせてインストーラを落としてくる
2. インストール画面で指示に従ってインストール(以下参考画像)

3. インストールが完了したらhogehogeを押してブラウザからTailscaleにログイン

4. 以下のような画面になればOK