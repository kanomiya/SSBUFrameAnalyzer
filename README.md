
# SSBUFrameAnalyzer

## Usage

```
python3 SSBUFrameAnalyzer.py DIGIT_DICTIONARY_FILE CHARA_DICTIONARY_FILE SCREENSHOT_FILE
```

1280x720のカラー画像のみ受け付けます（mainの場合内部で自動リサイズします）。

`DIGIT_DICTIONALY_FILE`、`CHARA_DICTIONARY_FILE`はそれぞれ、ダメージ値の数値画像から計算したHOG特徴量、対戦中のキャラ顔画像から計算したHOG特徴量を格納したjsonです（Releasesに添付）。あんまり検証してません。

いまのところ、2人、3人、4人対戦のみです。

## Requirements

- Tesseract
    - `apt install tesseract-ocr tesseract-ocr-jpn`
- pip install -r requirements.txt
    - Pillow
    - pyocr
    - numpy
    - scikit-image

