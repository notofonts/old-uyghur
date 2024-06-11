## FontBakery report

fontbakery version: 0.12.7



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSerifOldUyghur-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifOldUyghur/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[8] NotoSerifOldUyghur-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 310:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- finalHethdotaboveuyg

- finalHethdotaboveuyg.fina

- finalHethtwodotsaboveuyg

- finalHethtwodotsaboveuyg.fina

- gimelHethdotaboveuyg

- gimelHethdotaboveuyg.fina

- gimelHethdotaboveuyg.init

- gimelHethdotaboveuyg.medi

- gimelHethtwodotsaboveuyg

- gimelHethtwodotsaboveuyg.fina

- gimelHethtwodotsaboveuyg.init

- gimelHethtwodotsaboveuyg.medi

- nundotaboveuyg

- nundotaboveuyg.fina

- nundotaboveuyg.init

- nundotaboveuyg.medi

- sadheuyg.alt

- shintwodotsbelowuyg

- shintwodotsbelowuyg.fina

- shintwodotsbelowuyg.init

- shintwodotsbelowuyg.medi

- zayindotbelowuyg

- zayindotbelowuyg.fina

- zayintwodotsbelowuyg

- zayintwodotsbelowuyg.fina
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* memuyg.fina_leshuyg.fina: L&lt;&lt;280.0,0.0&gt;--&lt;278.0,0.0&gt;&gt; -&gt; L&lt;&lt;278.0,0.0&gt;--&lt;162.0,0.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers), Sar (Latn, 500,000 speakers), Makaa (Latn, 221,000 speakers), Vute (Latn, 21,000 speakers), Dii (Latn, 71,000 speakers), Navajo (Latn, 166,319 speakers), Bete-Bendi (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Gulay (Latn, 250,478 speakers), Ebira (Latn, 2,200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Dan (Latn, 1,099,244 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Zapotec (Latn, 490,000 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), South Central Banda (Latn, 244,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Bafut (Latn, 158,146 speakers), Mundani (Latn, 34,000 speakers), Nzakara (Latn, 50,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Yala (Latn, 200,000 speakers), Igbo (Latn, 27,823,640 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Mango (Latn, 77,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, old-permic, tifinagh, malayalam, syriac, coptic, tai-le, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: lepcha, zanabazar-square, gunjala-gondi, khojki, oriya, masaram-gondi, arabic, duployan, brahmi, hebrew, cham, tibetan, malayalam, tagalog, tirhuta, phags-pa, kaithi, nko, javanese, sinhala, telugu, balinese, gujarati, modi, sharada, sogdian, syriac, thai, psalter-pahlavi, hanunoo, tai-le, kayah-li, warang-citi, saurashtra, chakma, buginese, buhid, siddham, tagbanwa, kannada, pahawh-hmong, dogra, tai-tham, hanifi-rohingya, yi, manichaean, myanmar, mongolian, grantha, khudawadi, lao, avestan, gurmukhi, newa, tai-viet, bhaiksuki, mahajani, mandaic, tamil, kharoshthi, batak, devanagari, limbu, tifinagh, thaana, new-tai-lue, rejang, takri, meetei-mayek, sundanese, bengali, hatran, syloti-nagri, khmer</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: math, old-permic, phags-pa, kaithi, javanese, telugu, music, hanunoo, kayah-li, warang-citi, pahawh-hmong, dogra, khudawadi, lao, newa, tai-viet, batak, devanagari, rejang, lepcha, symbols, duployan, adlam, cham, malayalam, tirhuta, caucasian-albanian, gujarati, thai, osage, tagbanwa, yi, manichaean, mongolian, coptic, bhaiksuki, limbu, thaana, new-tai-lue, meetei-mayek, syloti-nagri, khmer, zanabazar-square, khojki, brahmi, tibetan, marchen, tagalog, sinhala, soyombo, modi, syriac, psalter-pahlavi, canadian-aboriginal, saurashtra, chakma, buhid, mende-kikakui, siddham, tai-tham, gurmukhi, miao, tamil, mandaic, kharoshthi, bengali, gunjala-gondi, wancho, oriya, elbasan, armenian, masaram-gondi, hebrew, bassa-vah, nko, balinese, sogdian, sharada, tai-le, buginese, kannada, hanifi-rohingya, myanmar, grantha, ahom, mahajani, tifinagh, takri, sundanese</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>old-uyghur</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 8 | 115 | 6 | 118 | 0 | 
| 0% | 0% | 0% | 3% | 46% | 2% | 48% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
