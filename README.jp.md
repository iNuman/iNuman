<p align="right"><a href="https://github.com/iNuman">🌐 English</a></p>

# アリ・ノマン（Ali Noman）

<a href="https://github.com/iNuman">
  <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+JP&weight=500&size=15&duration=3000&pause=800&color=39D353&vCenter=true&width=600&lines=%E7%94%BB%E5%83%8F%E5%87%A6%E7%90%86%E3%81%AE%E7%A0%94%E7%A9%B6%E8%80%85;%E3%82%B3%E3%83%B3%E3%83%94%E3%83%A5%E3%83%BC%E3%82%BF%E3%83%93%E3%82%B8%E3%83%A7%E3%83%B3;%E5%8C%BB%E7%94%A8%E7%94%BB%E5%83%8F%E3%81%AE%E8%A7%A3%E6%9E%90;%E5%B0%8F%E3%81%95%E3%81%AACNN%E3%81%A8Transformer;10%E4%B8%87%E4%BA%BA%E3%81%8C%E4%BD%BF%E3%81%86%E3%82%A2%E3%83%97%E3%83%AA%E3%81%AE%E9%96%8B%E7%99%BA" alt="タイピングアニメーション" />
</a>

<ruby>電気通信大学<rt>でんきつうしんだいがく</rt></ruby>（UEC）で、<ruby>情報学<rt>じょうほうがく</rt></ruby>の<ruby>修士<rt>しゅうし</rt></ruby>の学生です。MEXT（<ruby>文部科学省<rt>もんぶかがくしょう</rt></ruby>）の<ruby>奨学金<rt>しょうがくきん</rt></ruby>で勉強しています。

小さくて、どこでも動く画像AIのモデルを作っています。学習していないデータでも、正しく動くことを大切にしています。研究の前は、2年間モバイルエンジニアとして働き、10万人以上が使うアプリにAIの機能を作りました。モデルと製品、どちらもできます。

---

## 研究

**CoLaRT**：<ruby>網膜<rt>もうまく</rt></ruby>の病気をいくつも同時に見つける、小さなCNNとTransformerのモデル<br>
*IEEE ICPRS 2027 に<ruby>投稿<rt>とうこう</rt></ruby>しました*

- ラベルトークンを使うので、画像が大きくなってもトークンの数は増えません
- 小さなバックボーン：ConvNeXtV2-Pico、InceptionNeXt-Atto
- 計算の量（GFLOPs）は、DenseNet201を使ったC-Tranより67%少なく、ResNet152dを使ったものより88%少ないです（384×384）
- 2つのモデルを合わせると、MuReDで **0.708 mAP / 0.943 AUC** です（3回の平均、512×512）

**研究で大切にしていること**

- 平均の点数だけでなく、病気ごとに結果を見ます
- 何回も実験して、その平均を出します
- 前の<ruby>論文<rt>ろんぶん</rt></ruby>の方法を自分で作り直して、正しく比べます
- Grad-CAMで、モデルが画像のどこを見ているか、たしかめます

---

## 開発の仕事

**Convo Corp. モバイルエンジニア（2023年〜2025年）**

- [SkinCheck](https://apps.apple.com/us/app/skin-check-dermatology-care/id1468215066)：写真をとる所から、画像の<ruby>前処理<rt>まえしょり</rt></ruby>、Vertex AIでの判定まで、ひふを見るしくみを作りました。明るいはだにも、暗いはだにも使えるモデルを入れました。
- [BeMe](https://play.google.com/store/apps/details?id=com.bememultiplatform.android)：AIアシスタントのアプリの機能を作りました
- [Convo](https://play.google.com/store/apps/details?id=com.convo.android)：チームで話すアプリの機能を作りました
- [Energy Radio KSA](https://play.google.com/store/apps/details?id=com.energyradioksa)：Androidアプリを作りました

また、スマホの中で動く顔<ruby>認識<rt>にんしき</rt></ruby>を作り、サーバーの仕事を少なくしました。スマホの中で動く小さな言語モデルで、予定やメッセージを手伝う<ruby>試作<rt>しさく</rt></ruby>もしました。

**自分のプロジェクト**

- [PdfHighlighter](https://github.com/iNuman/PdfHighlighter)：PDFの文字に色をつけたり、文字を直したりできるAndroidのライブラリ（MuPDFを使用）
- [ScholarshipHunting](https://github.com/iNuman/ScholarshipHunting)
- [Lesson Quiz](https://inuman.github.io/lesson-quiz/)：日本語を勉強しながら作った、単語クイズのWebアプリ

---

## スキル

**研究：** Python, PyTorch, TensorFlow, Keras, OpenCV, scikit-learn, NumPy, Pandas, Matplotlib, Seaborn, CNN, Vision Transformer, Grad-CAM

**開発：** Kotlin, Java, Dart, Flutter, TypeScript, React Native, Firebase, Google Cloud, Vertex AI, Docker, Git, CI/CD

---

## <ruby>受賞<rt>じゅしょう</rt></ruby>・<ruby>奨学金<rt>しょうがくきん</rt></ruby>

- MEXT奨学金、日本<ruby>政府<rt>せいふ</rt></ruby>（2025年）
- 1位、UEC データマイニング Kaggle コンテスト（2026年）
- SEIKO奨学金、ポーランドのポズナン工科大学（2026年）
- ポスター発表、第55回 UEC International mini-Conference（2026年）
- 大学の<ruby>卒業論文<rt>そつぎょうろんぶん</rt></ruby>：スマホの中のAIで、ねむけを見つけるアプリ（2020年）

---

## GitHubの活動

<p align="center">
  <img src="https://gh-motion-card.vercel.app/api/github-motion?username=iNuman&theme=dark&shape=square&animation=glow&border_width=0&hide_rank=true&locale=ja" alt="GitHubの活動" width="100%" />
</p>

---

**メール：** inuumaan@gmail.com
**LinkedIn：** [linkedin.com/in/-inuman](https://www.linkedin.com/in/-inuman/)
**GitHub：** [github.com/iNuman](https://github.com/iNuman)
