# サブタイトルがある場合
<style>.con-sub{font-size:.8em; display:block; }</style>
<span class="con-sub">

# 業界本目次
<style>.size_tag{font-size:80%; }</style>
<span class="size_tag">

# 箇条書き
## パターン
<ul class = "toc">
<ul type = "disc">	●
<ul type = "circle">	◯
<ul type = "square">	■
<ol type = "番号等">	連番

## 箇条書きの内容
<li>
</li>

## 箇条書きの末尾
</ul>	記号
</ol>	連番

# フォントカラーの指定
<style>.note{color:red;}</style>
<span class="note">

## キーワード
black
silver
gray
white
maroon
red
purple
fuchsia
green
lime
olive
yellow
navy
blue
teal
aqua

# リンク
<a href = "URL">
</a>

## GitHub,Twitter
<a href = "https://github.com/アカウント名">
<a href = "https://twitter.com/アカウント名">

## 新しいタブで開く
target="_blank"

## ページ内の特定の場所
id="    "
<a href="#    ">

# 説明リスト
<dl>
	<dt>説明する言葉</dt>
	<dd>定義</dd>
</dl>

# 正誤表

## 文言の例
<p>本書の以下の部分に誤りがありました。ここに訂正するとともに，ご迷惑をおかけしたことを深くお詫び申し上げます。</p>

## 更新日時の右寄せ
<div align="right"><p>（2022年4月28日最終更新）</p></div>

## 古い更新
<!--
<div class="partition-block"><p>（以下2022年4月1日更新）</p></div>
-->

## 表
<h4>ページ</h4>
<table class="errataTable" cellspacing="0"><tbody>
	<tr><th>誤</th>
		<td>修正対象</td>
	</tr>
	<tr><th>正</th>
		<td>修正後</td>
	</tr>
</tbody></table>

### 修正部分の強調
<strong>
</strong>

### コード
<div class="preWrap"><pre><code>
</code></pre></div>

# サンプルファイルのダウンロード
## パスワードなし
<p>本書のサンプルファイルをダウンロードできます。</p>

<p>データは，圧縮ファイル形式でダウンロードできます。<br />
圧縮ファイルをダウンロードしていただき，適宜展開してご利用ください。</p>

<dl>
	<dt>ダウンロード</dt>
	<dd><a href="[+GHsiteSelect+]/files/book/.../sample.zip">サンプルファイル</a></dd>
</dl>

## パスワードあり
[!authDownload? &user=`    ` &pass=`    ` &file=`/files/book/.../sample.zip`!]
[!authDownload? &file=`/files/book/.../download/auth/sample.zip` &key=`    :    `!]

## 注
<dl class="footNote">
<dt>免責</dt>
<dd>本サンプルを使用することによって，使用者が受けたあらゆる不利益に対して，原著者および技術評論社はその責任を負いません。</dd>
</dl>

# 閲覧制限
[[authPage? &key=`    `]]
<div>[!authPage?  &key=`    ` &visible=`0`!]</div>

# 枠

## 点線
<div style="padding: 10px; margin-bottom: 10px; border: 1px dotted #333333;">
<div style="padding: 10px; margin-bottom: 10px; border: 1px dashed #333333;">

## 実線
<div style="padding: 10px; margin-bottom: 10px; border: 1px solid #333333;">
<div style="padding: 10px; margin-bottom: 10px; border: 1px solid #333333; border-radius: 10px;">

## 二重線
<div style="padding: 10px; margin-bottom: 10px; border: 5px double #333333;">
<div style="padding: 10px; margin-bottom: 10px; border: 5px double #333333; border-radius: 10px;">

# 画像掲載

<div class="illust">
<p>▼図1_1　コラボレーター・コミュニティにおけるインナーとアウターの図</p>
<p><img src="[+GHsiteSelect+]/files/book/2022/978-4-297-12769-5/download/1-1.png" alt="図1_1" title="図1_1" width="400"></p>
</div>

[[imageLightbox? &alt=`pc_01.png` &title=`pc_01.png` &width=`400` &src=`assets/files/book/2020/978-4-297-11700-9/FE_Master1.png`]]

# Google code prettify

<script src="https://cdn.jsdelivr.net/gh/google/code-prettify@master/loader/run_prettify.js"></script>

## コード

<pre class="prettyprint">
<code>

</code>
</pre>

## スキン

?skin=desert
?skin=sunburst
?skin=sons-of-obsidian
?skin=doxy

## 行番号あり

<pre class="prettyprint linenums">
<code>

</code>
</pre>

## 行番号途中から

<pre class="prettyprint linenums: ">
<code>

</code>
</pre>

# 文字実体参照
&	&amp;
©	&copy;
®	&reg;
™	&trade;
"	&quot;
'	&apos;
<	&lt;
>	&gt;
 	&nbsp;
https://tech-unlimited.com/escape.html
