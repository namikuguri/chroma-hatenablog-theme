# CHROMA Style for Hatena Blog
CHROMA Style は、はてなブログ [CHROMA](http://chroma.hatenablog.com/) 用に作成したデザインテーマです。

他のブログにこのスタイルを適用すると、はてなモジュールが含まれているブログのフッター（ `#box2` ）あたりがうまく表示されません。  
ただし、以下の並びではてなモジュールを追加している場合は、おそらくフッターも CHROMA と同じように表示されると思います。

- 検索モジュール
- プロフィールモジュール

## スタイルの適用方法
はてなブログのダッシュボードから `デザイン -> カスタマイズ -> デザインCSS` に進み、以下のはてなブログ元々のコードに続けて貼り付けます。

```css
/* <system section="theme" selected="alpha2"> */
@import "/css/theme/alpha2/alpha2.css";
/* </system> */

/* <system section="background" selected="default"> */
/* default */
/* </system> */

/* === ここにスタイルシートのコードを貼り付ける === */
```

## ドキュメント
デザインルールは [/doc/design-rule.md]() に書いています。  
CSS の構造は [/doc/css-constitution.md]() に書いています。

他のちょこっとしたことは[ブログ](http://chroma.hatenablog.com/)に書き残しています。
