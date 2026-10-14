# 今井久一郎 社会保険労務士事務所 — 公式ホームページ

千葉市美浜区の社労士事務所「CSI&LC IMAI」の静的ウェブサイトです。  
GitHub Pages でホスティングしています。

**公開URL:** https://sr-imai-office.com/

---

## ディレクトリ構成

```
03 ホームページ/
├── index.html           # トップページ
├── about.html           # 事務所紹介・代表プロフィール
├── services.html        # サービス一覧
├── serviceAbaut.html    # サービス詳細
├── kintaiservice.html   # 勤怠管理システム導入支援
├── career.html          # キャリアサポート
├── contact.html         # お問い合わせフォーム
├── privacy.html         # プライバシーポリシー
├── thanks.html          # お問い合わせ送信完了
├── sitemap.xml          # サイトマップ（SEO用）
├── robots.txt           # クローラー制御
├── images/              # 画像ファイル
├── pdf/                 # PDFダウンロード資料
├── blog/                # コラム・記事一覧
│   ├── index.html       # ブログ一覧ページ
│   ├── article-template.html  # 新記事作成テンプレート
│   └── *.html           # 各コラム記事
├── template/            # ページテンプレート
└── backup/              # バックアップファイル
```

---

## ブログ記事一覧

| ファイル名 | タイトル（概要） |
|---|---|
| saitei-chingin-2026.html | 最低賃金 2026年版コラム |
| shakaihoken-2026.html | 社会保険手続き 2026年版 |
| 37-egov-gbizid-guide.html | 社会保険の電子申請（e-Gov）入門 |
| doitsu-chingin-2026.html | 同一労働同一賃金・待遇差の点検 |
| josekin-2026.html | 助成金 2026年版 |
| career-up-josekin-r8.html | キャリアアップ助成金 |
| 36kyotei-guide.html | 36協定ガイド |
| santei-kiso-todoke-2026.html | 算定基礎届 2026年版 |
| hokenryo-chosei.html | 保険料調整 |
| kinmu-system-guide.html | 勤怠システム導入ガイド |
| romu-dx-roadmap.html | 労務DXロードマップ |
| shugyo-kisoku-guide.html | 就業規則ガイド |
| fukugyo-roudoujikan.html | 副業・兼業と労働時間管理 |
| gyomu-bunseki-dankai_2.html | 業務分析 第2回（作成中） |

---

## 開発・更新の手順

### 新しいコラム記事を追加する場合

1. `blog/article-template.html` をコピーして新しいHTMLファイルを作成
2. 内容を編集してブログ記事ディレクトリ（`blog/`）に保存
3. `blog/index.html` に記事カードを追加
4. `sitemap.xml` に新しいURLを追加
5. 変更をコミット・プッシュ

### ページを更新する場合

1. 対象HTMLファイルを直接編集
2. ローカルでブラウザ確認
3. `git add`・`git commit`・`git push` で公開

---

## 使用技術

- **HTML / CSS / JavaScript** — フレームワーク不使用の静的サイト
- **GitHub Pages** — ホスティング
- **Google Analytics** (`G-1G9TEKC6Y2`) — アクセス解析
- **Google Search Console** — SEO管理
- **Schema.org 構造化データ** — リッチリザルト対応

---

## SEO・アクセス解析

| 項目 | 詳細 |
|---|---|
| Google Analytics ID | G-1G9TEKC6Y2 |
| Google サイト確認ファイル | google4d5ee6ee50a139cb.html |
| サイトマップ | https://sr-imai-office.com/sitemap.xml |

---

## 連絡先

今井久一郎 社会保険労務士事務所  
千葉市美浜区  
メール: imai.504826@gmail.com
