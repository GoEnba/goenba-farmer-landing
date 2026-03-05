# farmer-landing.html 使用画像一覧

**作成日**: 2026-02-25
**更新日**: 2026-03-04（画像差し替え実施）
**確認者**: Claude Code

---

## 画像差し替え履歴

### 2026-03-04 画像差し替え
- ヒーローセクション・Our Mission以外の6枚を文言に合致する画像に差し替え
- 旧画像は `images/backup/` にバックアップ済み

### 2026-02-25 画像ローカル化
- すべてのUnsplash画像をローカルにダウンロードし、HTMLファイルのURLを書き換え

---

## 使用画像の全リスト

### 1. ロゴ画像
| ファイル名 | サイズ | 使用箇所 | 出典 |
|-----------|------|---------|------|
| goenba-logo.jpg | 426KB (3709x2681px) | ヘッダー、フッター | 要確認 |

### 2. 変更なしの画像
| ファイル名 | サイズ | 使用箇所 | alt属性 | 元URL（Unsplash） |
|-----------|------|---------|---------|------------------|
| hero-bg.jpg | 348KB | Hero背景（CSS） | - | photo-1500382017468-9049fed747ef |
| mission-bg.jpg | 1.0MB | ミッションセクション | - | photo-1523741543316-beb7fc7023d8 |

### 3. 差し替え済み画像（2026-03-04）

| ファイル名 | サイズ | 使用箇所 | alt属性 | 内容 | Unsplash ID |
|-----------|------|---------|---------|------|-------------|
| about-support.jpg | 130KB (1200x580) | Aboutカード1 | 魅力発信代行 | 田んぼでラップトップを操作する農家 | o_tWu03QY9Y |
| about-lowcost.jpg | 128KB (1200x800) | Aboutカード2, Feature2 | ページ作成代行 | オフィスでPC作業する2人 | gVtJgTyi2iI |
| about-direct.jpg | 83KB (1200x800) | Aboutカード3, Feature2 | お客様対応代行 | ヘッドセットのCSスタッフ | ieayo480x78 |
| feature-support.jpg | 80KB (1200x800) | Feature1 | ブランディング・コンテンツ制作 | ノートに鉛筆で執筆中 | RdmLSJR-tq8 |
| feature-direct.jpg | 217KB (1200x1800) | Feature3 | スマホでSNS操作・簡単出品 | スマホでSNSストーリーを操作 | GPJwAHd8maE |
| cta-bg.jpg | 139KB (1200x675) | CTA背景（CSS） | - | 農家がAIタブレットで作物監視 | NU_s4KI_zME |

**差し替え後合計**: 8ファイル、約1.3MB（旧: 2.3MB → 軽量化）

---

## バックアップ

旧画像は `images/backup/` に保存：
- about-support.jpg (148KB)
- about-lowcost.jpg (41KB)
- about-direct.jpg (157KB)
- feature-support.jpg (71KB)
- feature-direct.jpg (118KB)
- cta-bg.jpg (395KB)

---

## 残タスク

### 1. goenba-logo.jpg
- [ ] 出典・著作権の確認
- [ ] 拡張子と実際の形式の不一致を修正（PNG形式なのに.jpg）

### 2. 今後の改善案（任意）
- [ ] 画像の最適化（WebP形式への変換でさらに軽量化）
- [ ] 実際の農家の写真を使用してブランドの信頼性向上
- [ ] about-support.jpgのアスペクト比改善（現在1200x580で横長）

---

## Unsplashライセンスについて

- **商用利用**: 可能
- **クレジット表記**: 推奨（必須ではない）
- **ライセンス詳細**: [Unsplash License](https://unsplash.com/license)
