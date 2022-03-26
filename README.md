# alias
日本語IMEが有効な状態でコマンドを書き始めてしまったときのイライラ回避用
# コレはなに
「`ls`と打とうとして`ｌｓ`となってしまった」とか「`ffmpeg`と打とうとして`っｆｍぺｇ`になってしまった」というようなミスに対抗するためのLinux向けエイリアスです。~~F10押せばいいのにという声は聞かなかったことにする。~~

上記とは別に`sudo apt update;sudo apt upgrade`を`更新`などと、思い切って短縮したコマンドも含まれます。
# 詳細
`anti`リスト、`short`リスト、`japanese`リストをBash･Zshの起動時に読み込むことでエイリアスを使用することができます。

`anti`･･･`ｌｓ`を`ls`、`くｒｌ`を`curl`などと読み替えるエイリアス

`japanese`･･･`sudo apt update;sudo apt upgrade`を`更新`などと、日本語をコマンドに使用するエイリアス

`short`･･･`microsoft-edge`を`Edge`、`code`を`VScode`などと、大文字を利用して認識しやすいコマンド名にするエイリアス
# 使い方（例）
1,`git clone https://github.com/Npepperlinux/alias.git`

2,

Bashの場合:`echo -e "source ~/alias/anti\nsource ~/alias/short\nsource ~/alias/japanese" >> ~/.bashrc`

Zshの場合:`echo -e "source ~/alias/anti\nsource ~/alias/short\nsource ~/alias/japanese" >> ~/.zshrc`

3,ターミナルの再起動後に使用可能になります。

# 注意
気まぐれに更新します。

aliasのリストの中身は作成順となります。

内容自体は大したものでは無いのでご自由にお使いください（自己責任でお願いします）。
