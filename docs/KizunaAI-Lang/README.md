# キズナアイ言語 ლ(´ڡ`ლ)

[<img align="right" src="https://user-images.githubusercontent.com/39142850/73865548-c7048080-4886-11ea-818b-288bad649684.jpeg" alt="KizunaAI" width="390">](https://www.youtube.com/channel/UC4YaOt1yT-ZeyB0OmxHgolA)

インテリジェントなスーパーA.I.『キズナアイ言語』<br>
gem『r-fxxk』を使用したBrainfuck系言語です。

- [A.I.Channel - YouTube](https://www.youtube.com/channel/UC4YaOt1yT-ZeyB0OmxHgolA)  
- [Kizuna AI - Twitter](https://twitter.com/aichan_nel)<br>
<br>

## 使用ライブラリ & 本家

- [masarakki / r-fxxk](https://github.com/masarakki/r-fxxk)<br>
- [いつもニコニコあなたの隣に這いよる混沌ニャルラトホテプ言語ですっ](https://github.com/masarakki/nyaruko_lang)<br>
<br>

## 実行

```
gem install r-fxxk
./kizunaai helloworld.kizunaai
```

> Hello World!
<br>

## キズナアイ言語

| 構文 | 言語仕様 |
|--|--|
| はいどうもー! | ポインタを右へ移動 |
| 最高かよ! | ポインタの指す値を1増やす |
| ふぁっきゅー | ポインタを左へ移動 |
| アイた〜んビーム!! | ポインタの指す値を1減らす |
| お・ね・が・い | ポインタの指す値が0なら 対応する '完璧ですね!' までジャンプ |
| 完璧ですね! | ポインタの指す値が0で無いなら 対応する 'お・ね・が・い' までジャンプ |
| 危機回避〜! | ポインタの指す値を出力する |
| ちょちょいのちょいですよ | 入力から1バイト読み込む|
