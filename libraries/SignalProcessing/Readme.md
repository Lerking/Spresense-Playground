#信号処理ライブラリとMultiCoreのサンプル

-------------------------

v1.3.0 で、ArduinoでのMultiCoreが可能になったので、
FFT、IIRをはじめとする信号処理のライブラリを一新しました。


## FFT
FFTライブラリは、CMSIS-DSPが取り込まれたので、こちらをそのまま呼ぶことで、
開発者が自由に実装できるようにコードでの提供をします。
これにより、DSPのインストールなどはなくなりました。

いくつかサンプルを作成しUpしています。

・ピーク周波数の検出
・特定周波数音声の検出
・FFT/iFFTを用いたVoiceChanger


## IIR
IIRライブラリは、新規に追加しました。
基本、FFTと同じ構造にしています。
まずは、16bitのみ対応。
その後、32bitも対応します。

サンプルは、以下。

・LPF
・HPF



