# CATs-TAIL 

CATs-TAIL (Collection of Analysis Tools for Testing Astronomical Imaging Large data) は可視光/近赤外の天文撮像データに対して、よく行う解析をするためのコードをまとめたレポジトリです。
python で書いていますが、[SExtractor](https://github.com/astromatic/sextractor) を一部のコードで必要とします。
また、このコードはすばる望遠鏡の Hyper Suprime-Cam (HSC) で観測された撮像データに対して実行することをかなり意識しています。
もちろん、それ以外の望遠鏡の解析にも使えるようにしています。
各コードの大雑把な説明は以下に載せています。詳細については、各ディレクトリ以下の README をご確認ください。
<br>
 

## meas_limitmag

限界等級を測定するためのコードです。
