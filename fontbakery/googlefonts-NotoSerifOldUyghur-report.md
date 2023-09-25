## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[10] NotoSerifOldUyghur-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, malayalam, tifinagh, math, old-permic, coptic, tai-le, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: sinhala, yi, meetei-mayek, brahmi, chakma, kharoshthi, cham, telugu, hanunoo, duployan, khudawadi, mongolian, nko, sharada, sundanese, bengali, avestan, new-tai-lue, phags-pa, saurashtra, mahajani, hatran, pahawh-hmong, gujarati, gunjala-gondi, takri, balinese, kaithi, thaana, newa, tai-tham, grantha, psalter-pahlavi, tagbanwa, hanifi-rohingya, dogra, tamil, devanagari, manichaean, tifinagh, myanmar, buginese, mandaic, batak, thai, khmer, siddham, sogdian, modi, tai-le, kannada, limbu, rejang, oriya, tibetan, gurmukhi, tagalog, khojki, tai-viet, malayalam, tirhuta, lepcha, buhid, kayah-li, syloti-nagri, javanese, warang-citi, syriac
 * U+25CC DOTTED CIRCLE: try adding one of: brahmi, hanunoo, khudawadi, bengali, elbasan, soyombo, gujarati, takri, coptic, newa, mandaic, khmer, osage, tai-le, limbu, zanabazar-square, math, lepcha, javanese, meetei-mayek, mongolian, new-tai-lue, mahajani, pahawh-hmong, balinese, grantha, bhaiksuki, dogra, devanagari, myanmar, thai, mende-kikakui, sogdian, modi, rejang, tibetan, gurmukhi, khojki, sinhala, yi, music, chakma, ahom, marchen, nko, symbols, kaithi, hebrew, thaana, tagbanwa, hanifi-rohingya, caucasian-albanian, manichaean, old-permic, kayah-li, kharoshthi, cham, miao, telugu, duployan, sharada, sundanese, bassa-vah, lao, phags-pa, gunjala-gondi, adlam, psalter-pahlavi, wancho, tamil, tifinagh, buginese, batak, masaram-gondi, siddham, kannada, oriya, tagalog, tai-viet, malayalam, tirhuta, buhid, syloti-nagri, syriac

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `old-uyghur` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Old Uyghur' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- finalHethdotaboveuyg

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
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 dotaboveuyg (U+10F82), dotbelowuyg (U+10F83), twodotsaboveuyg (U+10F84) and twodotsbelowuyg (U+10F85) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

	* comma (U+002C): X=114.0,Y=1.0 (should be at cap-height 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at cap-height 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at cap-height 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at cap-height 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at cap-height 0?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at x-height 0?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at cap-height 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at x-height 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at cap-height 0?)

	* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=77.0,Y=1.0 (should be at cap-height 0?)

	* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

	* section (U+00A7): X=101.0,Y=2.0 (should be at cap-height 0?)

	* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=519.0,Y=1.5 (should be at cap-height 0?)

	* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

	* gbreve (U+011F): X=161.0,Y=-0.5 (should be at cap-height 0?)

	* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at cap-height 0?)

	* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at cap-height 0?)

	* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=519.0,Y=1.5 (should be at cap-height 0?)

	* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at cap-height 0?)

	* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

	* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at cap-height 0?)

	* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at cap-height 0?)

	* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at cap-height 0?)

	* u10AF2 (U+10AF2): X=575.5,Y=-1.0 (should be at baseline 0?)

	* u10AF2 (U+10AF2): X=575.5,Y=-1.0 (should be at cap-height 0?)

	* u10AF2 (U+10AF2): X=426.5,Y=1.0 (should be at baseline 0?)

	* u10AF2 (U+10AF2): X=426.5,Y=1.0 (should be at cap-height 0?)

	* bethuyg (U+10F71): X=610.0,Y=-1.0 (should be at baseline 0?)

	* bethuyg (U+10F71): X=610.0,Y=-1.0 (should be at cap-height 0?)

	* wawuyg (U+10F73): X=5.0,Y=-2.0 (should be at baseline 0?)

	* wawuyg (U+10F73): X=5.0,Y=-2.0 (should be at cap-height 0?)

	* zayinuyg (U+10F74): X=10.0,Y=-2.0 (should be at baseline 0?)

	* zayinuyg (U+10F74): X=10.0,Y=-2.0 (should be at cap-height 0?)

	* finalHethuyg (U+10F75): X=382.0,Y=-1.0 (should be at baseline 0?)

	* finalHethuyg (U+10F75): X=382.0,Y=-1.0 (should be at cap-height 0?)

	* yodhuyg (U+10F76): X=10.0,Y=-2.0 (should be at baseline 0?)

	* yodhuyg (U+10F76): X=10.0,Y=-2.0 (should be at cap-height 0?)

	* memuyg (U+10F79): X=207.0,Y=-1.0 (should be at baseline 0?)

	* memuyg (U+10F79): X=207.0,Y=-1.0 (should be at cap-height 0?)

	* memuyg (U+10F79): X=10.0,Y=-1.0 (should be at baseline 0?)

	* memuyg (U+10F79): X=10.0,Y=-1.0 (should be at cap-height 0?)

	* reshuyg (U+10F7E): X=10.0,Y=-1.0 (should be at baseline 0?)

	* reshuyg (U+10F7E): X=10.0,Y=-1.0 (should be at cap-height 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 9 | 121 | 7 | 111 | 0 |
| 0% | 0% | 4% | 49% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
