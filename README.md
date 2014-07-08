# CHROMA Style for Hatena Blog
CHROMA Style は、[CHROMA](http://chroma.hatenablog.com/) （はてなブログ）用に作成したデザインテーマです。

他のはてなブログにこのスタイルを適用すると、はてなモジュールが含まれているブログのフッター（ `#box2` ）あたりがうまく表示されません。  
ただし、以下の並びではてなモジュールを追加している場合は、おそらくフッターも CHROMA と同じように表示されると思います。

- 検索モジュール
- プロフィールモジュール

また、ブログの設定や記事の書き方によってデザインが崩れる可能性があります。

## スタイルの適用方法
はてなブログのダッシュボードから `デザイン -> カスタマイズ -> デザインCSS` に進み、以下のはてなブログ元々のコードに続けて[style.css](https://github.com/thleap/chroma-style-for-hatenablog/blob/master/style.css)貼り付けます。

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
デザインルールは [design-rule.md](https://github.com/thleap/chroma-style-for-hatenablog/blob/master/doc/design-rule.md) に書いています。  
CSS の構造は [css-constitution.md]https://github.com/thleap/chroma-style-for-hatenablog/blob/master/doc/css-constitution.md() に書いています。

他のちょこっとしたことは[ブログ](http://chroma.hatenablog.com/)に書き残しています。
