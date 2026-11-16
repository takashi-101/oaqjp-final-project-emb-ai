# Final Project

IBM の講座の最終課題用リポジトリ（[ibm-developer-skills-network/oaqjp-final-project-emb-ai](https://github.com/ibm-developer-skills-network/oaqjp-final-project-emb-ai)）をフォークしたものです。講座の演習の提出物で、自作のツールではありません。自作のツールは[プロフィール](https://github.com/takashi-101)にまとめています。

## このリポジトリにあるもの

- `EmotionDetection/emotion_detection.py`：文章を Watson NLP の感情判定サービス（講座の演習環境のもの）に送り、5つの感情（anger・disgust・fear・joy・sadness）の点数と、最も点数の高い感情を返す関数 `emotion_detector`。サービスが 400 を返したときは、すべての値を `None` にして返します。
- `EmotionDetection/__init__.py`：上の関数をパッケージとして読み込むためのファイル。
- `static/`、`templates/`：フォーク元にあった画面のひな形。

## ライセンス

フォーク元と同じ Apache License 2.0（[LICENSE](LICENSE)）。
