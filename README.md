# BetterTweetDeck_settings
BetterTweetDeck's custom css code.

## Usage

①「BetterTweetDeck」>「オプション」を開きます。

②「カスタムCSS」欄を開き、以下のコードを添付し「変更を保存する」を選択すれば反映されます。

```css:style.css
html section.column:first-child {
    width: 700px;
}
.column:first-child .item-box {
    height: 32px;
    overflow-x: auto;
    overflow-y: hidden;
}
.fullname {
    display: none;
}
.column:first-child .item-box:hover {
    height: auto;
}
.column:first-child .item-box:hover .tweet-context {
    display: block;
}
.tweet-context {
    display: none;
}
```
