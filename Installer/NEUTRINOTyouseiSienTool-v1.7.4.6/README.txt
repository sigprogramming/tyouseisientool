　=======================
　NEUTRINO調声支援ツール
　Version: 1.7.4.6
　=======================

　本ソフトウェアはNEUTRINOをGUIで扱えるようにするため、
　またピッチやタイミング等の中間ファイルを編集するために作成したものです。
　公式のものではありません。使用は下記をお読みの上、自己責任でお願いします。
　NEUTRINOの基本的な使い方については、NEUTRINO公式サイトをご確認ください。
　また、NEUTRINOの仕様変更により使用できなくなる可能性があります。

　※十分にテストできていないため、不具合がある可能性があります。バックアップを取った上でご使用ください。
　　不具合を発見された方は私のTwitter（@m_sig_tw）にご報告いただけると助かります

　・動作環境
　　.NET Framework 4.8がインストールされているWindows10以降のPC
　　以下の環境で動作確認を行っています。
　　　OS  : Windows 10 Home 64bit バージョン21H1
　　　CPU : Ryzen5 3500
　　　GPU : GeForce GTX1660Super
　　　RAM : 16.0GB

　・インストール方法
　　インストーラーでのインストールは不要です。
　　好きな場所へフォルダを移動してお使いください。
　　※環境設定でNEUTRINOフォルダの設定が必要です。

　・スコア編集時の注意
　　スコアの保存はMusicXMLの上書きとなります。
　　上書き前のMusicXMLはバックアップされます。
　　また、連符ありで書き出したMusicXMLをMuseScoreで読み込むと
　　エラー表示が出てクオンタイズされます。
　　そのため、MusicXMLは別フォルダに保存しておいて、ドラッグ&ドロップで
　　読み込むことをおすすめします。（NEUTRINOのscoreフォルダにない場合は
　　自動でコピーされます。）別フォルダのMusicXMLをMuseScore等で編集した場合は、
　　再度ドラッグ&ドロップするか、手動でscoreフォルダにコピーし直してください。

　・免責事項
　　本ソフトを使用したことによる一切の損害に対し、作成者は責任を負いません。
　　動作確認はしていますが、動作の保証はいたしません。

　・本ソフトウェアの作成者
　　SIG（@m_sig_tw）　

　・NEUTRINOについて
　　NEUTRINOの製作者様：SHACHI（@SHACHI_NEUTRINO）
　　NEUTRINO公式サイト：https://n3utrino.work/

　・謝辞
　　歌声合成エンジンを作ってくださったSHACHI様に感謝します。
　　また、以下のライブラリを使わせてもらっています。製作者様に感謝します。
　　音声出力にMark Heath氏のNAudioを使用しています。
　　　https://github.com/naudio/NAudio
　　UIにJames Willock氏のMaterial Design In XAML Toolkitを使用しています。
　　　https://github.com/MaterialDesignInXAML/MaterialDesignInXamlToolkit
　　MVVMでの実装にneuecc氏, xin9le氏, okazuki氏のReactivePropertyを使用しています。
　　　https://github.com/runceel/ReactiveProperty
