<p align="right">
  <a href="https://github.com/iNuman"><img src="https://img.shields.io/badge/English-%E8%8B%B1%E8%AA%9E-0D1117?style=for-the-badge&logo=googletranslate&logoColor=39D353&labelColor=0D1117&color=161B22" alt="English" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0D1117,50:0E3B2E,100:39D353&text=Ali%20Noman&fontColor=FFFFFF&fontSize=58&fontAlignY=36&animation=fadeIn&desc=%E7%94%BB%E5%83%8F%E5%87%A6%E7%90%86%20%7C%20%E3%82%B3%E3%83%B3%E3%83%94%E3%83%A5%E3%83%BC%E3%82%BF%E3%83%93%E3%82%B8%E3%83%A7%E3%83%B3%20%7C%20MLLM%E3%83%BBVLM&descSize=18&descAlignY=58" width="100%" alt="アリ・ノマン" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+JP&weight=500&size=17&duration=3000&pause=800&color=39D353&center=true&vCenter=true&width=620&lines=%E7%94%BB%E5%83%8F%E5%87%A6%E7%90%86%E3%81%AE%E7%A0%94%E7%A9%B6%E8%80%85;%E3%82%B3%E3%83%B3%E3%83%94%E3%83%A5%E3%83%BC%E3%82%BF%E3%83%93%E3%82%B8%E3%83%A7%E3%83%B3;%E5%8C%BB%E7%94%A8%E7%94%BB%E5%83%8F%E3%81%AE%E8%A7%A3%E6%9E%90;%E3%83%9E%E3%83%AB%E3%83%81%E3%83%A2%E3%83%BC%E3%83%80%E3%83%ABLLM%E3%81%A8VLM;%E5%B0%8F%E3%81%95%E3%81%AACNN%E3%81%A8Transformer;10%E4%B8%87%E4%BA%BA%E3%81%8C%E4%BD%BF%E3%81%86%E3%82%A2%E3%83%97%E3%83%AA%E3%81%AE%E9%96%8B%E7%99%BA" alt="タイピングアニメーション" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/%E9%9B%BB%E6%B0%97%E9%80%9A%E4%BF%A1%E5%A4%A7%E5%AD%A6-%E6%83%85%E5%A0%B1%E5%AD%A6_%E4%BF%AE%E5%A3%AB-161B22?style=flat-square&labelColor=0D1117&color=0E3B2E" />
  <img src="https://img.shields.io/badge/MEXT-%E5%A5%A8%E5%AD%A6%E7%94%9F-161B22?style=flat-square&labelColor=0D1117&color=0E3B2E" />
  <img src="https://img.shields.io/badge/Kaggle-1%E4%BD%8D-161B22?style=flat-square&logo=kaggle&logoColor=20BEFF&labelColor=0D1117&color=0E3B2E" />
  <img src="https://img.shields.io/badge/IEEE_ICPRS_2027-%E6%8A%95%E7%A8%BF%E6%B8%88%E3%81%BF-161B22?style=flat-square&labelColor=0D1117&color=0E3B2E" />
</p>

<p align="center">
小さくて、どこでも動く画像AIのモデルを作っています。<br>
学習していないデータでも、正しく動くことを大切にしています。<br>
研究の前は2年間、<b>10万人以上</b>が使うアプリにAIの機能を作りました。<br>
モデルと製品、どちらもできます。
</p>

---

## 🔬 研究

<table>
<tr>
<td width="62%" valign="top">


### CoLaRT
**<ruby>網膜<rt>もうまく</rt></ruby>の病気をいくつも同時に見つける、小さなCNNとTransformerのモデル**<br>
*IEEE ICPRS 2027 に<ruby>投稿<rt>とうこう</rt></ruby>しました*

- ラベルトークンを使うので、画像が大きくなってもトークンの数は増えません
- 小さなバックボーン：ConvNeXtV2-Pico、InceptionNeXt-Atto
- MuReDで、3回の平均（512×512）

<p>
  <img src="https://img.shields.io/badge/mAP-0.708-39D353?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/AUC-0.943-39D353?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/GFLOPs-%E2%88%9267%25_to_%E2%88%9288%25-39D353?style=for-the-badge&labelColor=0D1117" />
</p>

<sub>計算の量は、DenseNet201を使ったC-Tranより67%少なく、ResNet152dを使ったものより88%少ないです（384×384）</sub>

</td>
<td width="38%" valign="top">

### 研究で大切にしていること

- 🩺 **病気ごとに見る** · 平均の点数だけでなく、病気ごとに結果を見ます
- 🎲 **何回も実験** · 何回も実験して、その平均を出します
- ⚖️ **正しく比べる** · 前の<ruby>論文<rt>ろんぶん</rt></ruby>の方法を自分で作り直します
- 👁️ **Grad-CAM** · モデルが画像のどこを見ているか、たしかめます

</td>
</tr>
</table>

---

## 📱 開発の仕事

**Convo Corp. モバイルエンジニア** · 2023年〜2025年

- [**SkinCheck**](https://apps.apple.com/us/app/skin-check-dermatology-care/id1468215066) · 写真をとる所から、画像の<ruby>前処理<rt>まえしょり</rt></ruby>、Vertex AIでの判定まで、ひふを見るしくみ。明るいはだにも、暗いはだにも使えるモデルを入れました
- [**BeMe**](https://play.google.com/store/apps/details?id=com.bememultiplatform.android) · AIアシスタントのアプリの機能
- [**Convo**](https://play.google.com/store/apps/details?id=com.convo.android) · チームで話すアプリの機能
- [**Energy Radio KSA**](https://play.google.com/store/apps/details?id=com.energyradioksa) · Androidアプリの開発

また、スマホの中で動く顔<ruby>認識<rt>にんしき</rt></ruby>を作り、サーバーの仕事を少なくしました。スマホの中で動く小さな言語モデルで、予定やメッセージを手伝う<ruby>試作<rt>しさく</rt></ruby>もしました。

**自分のプロジェクト**

- [**PdfHighlighter**](https://github.com/iNuman/PdfHighlighter) · PDFの文字に色をつけたり、直したりできるAndroidのライブラリ（MuPDFを使用）
- [**ScholarshipHunting**](https://github.com/iNuman/ScholarshipHunting)
- [**Lesson Quiz**](https://inuman.github.io/lesson-quiz/) · 日本語を勉強しながら作った、単語クイズのWebアプリ

---

## 🛠️ 使う技術

**研究**

<p>
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,opencv,sklearn&theme=dark" />
</p>

<sub>ほかに Keras, NumPy, Pandas, Matplotlib, Seaborn, CNN, Vision Transformer, Grad-CAM</sub>

**開発**

<p>
  <img src="https://skillicons.dev/icons?i=kotlin,java,dart,flutter,ts,react,firebase,gcp,docker,git&theme=dark" />
</p>

<sub>ほかに Vertex AI, CI/CD</sub>

---

## 🏆 <ruby>受賞<rt>じゅしょう</rt></ruby>・<ruby>奨学金<rt>しょうがくきん</rt></ruby>

- 🎓 **MEXT奨学金** · 日本<ruby>政府<rt>せいふ</rt></ruby> · 2025年
- 🥇 **1位** · UEC データマイニング Kaggle コンテスト · 2026年
- 🌍 **SEIKO奨学金** · ポーランドのポズナン工科大学 · 2026年
- 🖼️ **ポスター発表** · 第55回 UEC International mini-Conference · 2026年
- 📄 **<ruby>卒業論文<rt>そつぎょうろんぶん</rt></ruby>** · スマホの中のAIで、ねむけを見つけるアプリ · 2020年

---

## 📈 GitHubの活動

<p align="center">
  <img src="https://gh-motion-card.vercel.app/api/github-motion?username=iNuman&theme=dark&shape=square&animation=glow&border_width=0&hide_rank=true&locale=ja" alt="GitHubの活動" width="100%" />
</p>

---

<p align="center">
  <a href="mailto:inuumaan@gmail.com"><img src="https://img.shields.io/badge/%E3%83%A1%E3%83%BC%E3%83%AB-inuumaan%40gmail.com-0D1117?style=for-the-badge&logo=gmail&logoColor=39D353&labelColor=0D1117&color=161B22" /></a>
  <a href="https://www.linkedin.com/in/-inuman/"><img src="https://img.shields.io/badge/LinkedIn-Ali_Noman-0D1117?style=for-the-badge&logo=linkedin&logoColor=39D353&labelColor=0D1117&color=161B22" /></a>
  <a href="https://github.com/iNuman"><img src="https://img.shields.io/badge/GitHub-iNuman-0D1117?style=for-the-badge&logo=github&logoColor=39D353&labelColor=0D1117&color=161B22" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:39D353,50:0E3B2E,100:0D1117" width="100%" />
</p>
