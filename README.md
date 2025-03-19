# diffusers-with-mps

sample diffusers in mac OS(with mps)

## overview

Huggingface の diffusers を mac OS 上で試します。

## environment

動作確認した環境は、以下の通りです。

- Python 3.10.12
- torch 2.6.0
- transformers 4.49.0
- accelerate 1.5.2
- diffusers 0.32.2

Python は arm64 版を使用しています。

Huggingface の diffusers を使うため、以下のライブラリをインストールします。

```bash
pip install diffusers torch transformers accelerate
```

## usage

以下のコマンドで diffusers を動かすことができます。

```bash
python main.py
```

生成画像は、PIL の Image オブジェクトとして出力されます
