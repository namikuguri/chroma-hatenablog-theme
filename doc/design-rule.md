# Design Rule
## Fonts
### Logo
フォントは [Comfortaa](https://www.google.com/fonts/specimen/Comfortaa) を使用し、文字間を `3px` 空けている。

### Site
フォントは `"Helvetica Neue", Helvetica, Arial, "ヒラギノ角ゴ Pro W3", "Hiragino Kaku Gothic Pro", "メイリオ", "Meiryo", sans-serif` の順に指定しいる。

### Code
フォントは `'Source Code Pro', Consolas, Menlo, Courier, monospace;` の順に指定しいる。

コードのシンタックスハイライトは次のようにカラーリングしている:

<table>
    <tr>
        <th>Class</th>
        <th>Hex</th>
        <th>Color</th>
    </tr>
    <tr>
        <td>.synSpecial</td>
        <td style="color:#FF00FF">#FF00FF</td>
        <td style="background:#FF00FF"></td>
    </tr>
    <tr>
        <td>.synType</td>
        <td style="color:#00B300">#00B300</td>
        <td style="background:#00B300"></td>
    </tr>
    <tr>
        <td>.synComment</td>
        <td style="color:#B3B3B3">#B3B3B3</td>
        <td style="background:#B3B3B3"></td>
    </tr>
    <tr>
        <td>.synPreProc</td>
        <td style="color:#4D00B3">#4D00B3</td>
        <td style="background:#4D00B3"></td>
    </tr>
    <tr>
        <td>.synIdentifier</td>
        <td style="color:#00B3B3">#00B3B3</td>
        <td style="background:#00B3B3"></td>
    </tr>
    <tr>
        <td>.synConstant</td>
        <td style="color:#CC0000">#CC0000</td>
        <td style="background:#CC0000"></td>
    </tr>
    <tr>
        <td>.synStatement</td>
        <td style="color:#CC7A00">#CC7A00</td>
        <td style="background:#CC7A00"></td>
    </tr>
</table>

## Size & Space
`line height ( 1.65 )` を基準にしたサイズ。  
小数部第三位以下は四捨五入する。

- xx-large ... 6.6(1.65 * 4 = 6.6)em
- x-large ... 3.3(1.65 * 2 = 3.3)em
- large ... 2.48(1.65 * 1.5 = 2.475)em
- midium ... 1.65em
- small ... 0.83(1.65 / 2 = 0.825)em
- x-small ... 0.41(1.65 / 4 = 0.4125)em
- xx-small ... 0.21(1.65 / 8 = 0.20625)em

### 例外

- `.categories` の `left` ... `5.8em` にしてる。`position` で相対位置を指定していて、 `.categories` の左の `.date` の幅を考慮する必要があるため。`.date` とは `0.83em` を取るようにしている。
- `.page-index .entry-title` ... `position` で相対位置を指定していて、 `.page-index .entry-title` の左の `.date` の幅を考慮する必要があるため。`.date:after` とは `0.41em` を取るようにしている。
- `.search-form`, `.search-result-form` の `input` の `width` と `button` の `width` と `height`  ... `2.07em` にしてる。幅と高さを指定して内側の余白を取るようにしているいるため、サイズは `1.65 + 0.21 * 2` で `2.07em` してる。`input` の `padding-right` は、左の `padding: 0.41em` に余白を合わせるため、 `2.07 + 0.41` で `2.48em` にしてる。
- `.entry-content ul`, `.entry-content ol` の `margin-left` ... `ul` は `margin-left: 1em` 、`ol` は `margin-left: 1.5em` にしてる。`list-style` で指定されたものを出すスペースを取るため。他の文章と左端を揃えるようにしてる。
- `.leave-comment-title:before`, `.pager-arrow` の `width` と `height` ... `1em` にしてる。文字サイズと同じ大きさでアイコンを出すため。

## Font Size
- Mobile: 100%
- Desktop: 112.5%
- Monitor: 131.3%

### Large, Medium, Small
- xx-large ... 200%
- ( only `h2` element ) ... 175%
- x-large ... 150%
- large ... 125%
- ( only `h4` element ) ... 112.5%
- midium ... 100%
- ( only `h6` element )... 87.5%
- small ... 75%

## Line-height
- Site Text ... 1.65
- Headings ... 1.25
- Preformatted Text ... 1.3

## Color
### Text
- text ... #383030
- text--pale ... #AFAFAF
- text-anchor ... #2961BC
- text-anchor--active ... #B13546
- text-anchor--visited ... #8734B1

### Background and Border
- main ... #FAFAFA
- main--darken ... #E8E8E8
- sub ... #FAFAE6
- sub--darken ... #F0F0D2
- key ... #B13546 ( Akane color )
- key--bright ... #CF3546
- key--darken ... #7F2132