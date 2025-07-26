---
marp: true
theme: default
paginate: true
backgroundColor: #ffffff
color: #333333
style: |
  section {
    background: #ffffff;
    font-family: 'Hiragino Sans', 'Yu Gothic UI', 'Meiryo UI', sans-serif;
    font-size: 28px;
    line-height: 1.6;
    padding: 60px;
    justify-content: start;

  }
  h1 {
    color: #2563eb;
    font-size: 48px;
    font-weight: 700;
    border-bottom: 4px solid #2563eb;
    padding-bottom: 15px;
    margin-bottom: 40px;
    text-align: left;
    position: absolute;
    top: 80px;
    left: 60px;
    right: 60px;
    margin-top: 0;
    z-index: 10;
  }
  section {
    position: relative;
    /* 既存のsectionスタイルはそのまま */
  }
  h2 {
    color: #1d4ed8;
    font-size: 36px;
    font-weight: 600;
    border-bottom: 3px solid #3b82f6;
    padding-bottom: 10px;
    margin-bottom: 30px;
  }
  ul {
    margin-left: 0;
    padding-left: 0;
  }
  li {
    list-style: none;
    margin-bottom: 15px;
    position: relative;
    padding-left: 30px;
  }
  li::before {
    content: "▸";
    color: #2563eb;
    font-weight: bold;
    position: absolute;
    left: 0;
  }
  strong {
    color: #1e40af;
    font-weight: 600;
  }
  .center {
    text-align: center;
  }
  .large-text {
    font-size: 36px;
    font-weight: 600;
  }
  .blue-box {
    background: #eff6ff;
    border: 2px solid #3b82f6;
    border-radius: 8px;
    padding: 20px;
    margin: 20px 0;
  }
  .code-sample {
    background: #f8fafc;
    border: 1px solid #e2e8f0;
    border-radius: 6px;
    padding: 20px;
    font-family: 'Consolas', 'Monaco', monospace;
    font-size: 20px;
    margin: 20px 0;
  }
  .image-placeholder {
    background: #e0f2fe;
    border: 2px dashed #0284c7;
    border-radius: 8px;
    padding: 40px;
    text-align: center;
    color: #0284c7;
    font-size: 24px;
    margin: 20px 0;
  }

---

# サンプルです

これはデザイン確認用のサンプルスライドです。


---
# タイトル
## 適当な見出し

- ここに適当なリスト
- なんでもいいです

<div class="blue-box">
サンプル用の青いボックスです。
</div>