# EVKartArduinoSimulink

　CQ EVカートをMATLAB、Simulinkでモデルベース開発しました。
制御基板はArduino MEGAです。具体的な制御ですが、ブラシレスモーターをホールセンサー有り120度矩形波通電で制御し、回転させました。

インバーター基板の上に今回手作りした治具基板を取り付け、更にその上にArduino　MEGAを取り付けてます。

■開発環境
 - MATLAB バージョン 9.7 (R2019b)　
 - Simulink バージョン 10.0 (R2019b)
 - Simulink Support Package for Arduino Hardware 19.2.3 

※技術書典9　サークル【k-abe】出版の書籍【EVカートで始めるモデルベース開発】の対象ハードウェアです。

※更新情報、補足情報はこちらです。
https://k-abe.hatenablog.com/

[![Github issues](https://img.shields.io/github/issues/grace2riku/EVKartArduinoSimulink)](https://github.com/grace2riku/EVKartArduinoSimulink/issues)
[![Github forks](https://img.shields.io/github/forks/grace2riku/EVKartArduinoSimulink)](https://github.com/grace2riku/EVKartArduinoSimulink/network/members)
[![Github stars](https://img.shields.io/github/stars/grace2riku/EVKartArduinoSimulink)](https://github.com/grace2riku/EVKartArduinoSimulink/stargazers)
[![Github top language](https://img.shields.io/github/languages/top/grace2riku/EVKartArduinoSimulink)](https://github.com/grace2riku/EVKartArduinoSimulink/)
[![Github license](https://img.shields.io/github/license/grace2riku/EVKartArduinoSimulink)](https://github.com/grace2riku/EVKartArduinoSimulink/)

# Demo

![Demo](resources/file-0.gif)

スロットルの代用品の可変抵抗を回すとモーターの回転数が高くなります。

# Advantages
　シンプルなモーター制御、コンパクトなSimulinkモデルなので次の利点があると考えています。
 - はじめてブラシレスモーターの制御を学習するのに最適
 - はじめてSimulinkモデルを学習する教材に最適

# Contributors
- [grace2riku](https://github.com/grace2riku)

