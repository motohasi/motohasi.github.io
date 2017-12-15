# macOS SierraでOS X Lionの日本語類語辞典を使う

類語辞典は、私の乏しい語彙を補ってくれ、言葉の関係を知るため気に入っている（英英でも類語辞典を愛用している）。macOSは標準で、知りたい言葉を強くクリック（もしくは三本指クリック）で、辞書を引けるので便利だ。しかし、OS X Mountain Lionから標準で、日本語の類語辞典がなく不便であった。そこで、OS X LionのインストールディスクからmacOS Sierraで類語辞典を使えるようにした。

1. Lion をダウンロードし、類語辞典をサルベージした。
[Mac OS X 10.8 Mountain Lionで失われた類語辞典を求めて | 配電盤](http://blog.unfindable.net/archives/5230)を参照し、行った作業である。

	1. App Store からOS X Lion をダウンロードする（ダウンロードできない場合は、次からの作業に進めない）。
	2. Applicationsフォルダにある「Mac OS X Lion install」をCtrl+クリックし「Show Package Contents」を選択する。
	3. Contents/SharedSupport/InstallESD.dmgをダブルクリックする。
	4. Terminal.app で以下の操作行った。
	
		> cd ~/Desktop #参照記事と同じ
		
		> pkgutil --expand "/Volumes/Mac OS X Install ESD/Packages/Essentials.pkg" ./tmp
	
		> ditto -x --bom ./tmp/Bom ./tmp/Payload ./
		
	5. Library/Dictionariesに類語辞典があるので、必要なフォルダにコピーする。
	
	6. Desktop にたくさんのフォルダができるので、全作業完了後削除する。
	
	ただし、macOS Sierra には、ルート直下の /Library/Dictionaries フォルダがなく、そこにフォルダを作って辞書ファイルをおいても使えなかった。

2. ホームディレクトリ直下の ~/Library/Dictionaries フォルダに辞書ファイルを置いた。
[奥村 晴彦先生のmacOSページ](https://oku.edu.mie-u.ac.jp/~okumura/macosx/)を参照した。

3. Dictionary.app の Preferences で類語辞典を選択する。


便利♪
