## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[9] NotoSerifLao[wdth,wght].ttf</summary>
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
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 48 in glyph 'two' has a kink between location wght=900,wdth=100 and location wght=100,wdth=62
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- uni0ECD.narrow
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifLao/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, syriac, tai-le, coptic, duployan, malayalam, old-permic, hebrew, math, tifinagh, todhri</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>lao</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Fur (Latn, 1,230,163 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Nateni (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers), Basaa (Latn, 332,940 speakers), South Central Banda (Latn, 244,000 speakers), Zapotec (Latn, 490,000 speakers), Ma’di (Latn, 584,000 speakers), Ejagham (Latn, 120,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Vute (Latn, 21,000 speakers), Lugbara (Latn, 2,200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Sar (Latn, 500,000 speakers), Ekpeye (Latn, 226,000 speakers), Makaa (Latn, 221,000 speakers), Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Mfumte (Latn, 79,000 speakers), Heiltsuk (Latn, 300 speakers), Koonzime (Latn, 40,000 speakers), Kom (Latn, 360,685 speakers), Navajo (Latn, 166,319 speakers), Mundani (Latn, 34,000 speakers), Han (Latn, 6 speakers), Southern Kisi (Latn, 360,000 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Aghem (Latn, 38,843 speakers), Yala (Latn, 200,000 speakers), Dii (Latn, 71,000 speakers), Avokaya (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Dan (Latn, 1,099,244 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* uni0E82 (U+0E82): X=106.5,Y=0.5 (should be at baseline 0?)

* uni0E82 (U+0E82): X=234.0,Y=1.0 (should be at baseline 0?)

* uni0E89 (U+0E89): X=319.0,Y=-0.5 (should be at baseline 0?)

* uni0E8C (U+0E8C): X=245.5,Y=1.0 (should be at baseline 0?)

* uni0E92 (U+0E92): X=598.5,Y=-0.5 (should be at baseline 0?)

* uni0E8A (U+0E8A): X=235.0,Y=1.0 (should be at baseline 0?)

* uni0E8A (U+0E8A): X=107.5,Y=0.5 (should be at baseline 0?)

* uni0E99 (U+0E99): X=295.5,Y=-2.0 (should be at baseline 0?)

* uni0E9D (U+0E9D): X=525.0,Y=716.0 (should be at cap-height 714?)

* uni0EA1 (U+0EA1): X=315.5,Y=-0.5 (should be at baseline 0?)

* uni0EA2 (U+0EA2): X=422.0,Y=715.0 (should be at cap-height 714?)

* uni0EA5 (U+0EA5): X=470.0,Y=1.5 (should be at baseline 0?)

* uni0EAA (U+0EAA): X=484.0,Y=1.5 (should be at baseline 0?)

* uni0EDC (U+0EDC): X=712.5,Y=2.0 (should be at baseline 0?)

* uni0EDD (U+0EDD): X=718.0,Y=-0.5 (should be at baseline 0?)

* uni0EB6 (U+0EB6): X=211.0,Y=713.0 (should be at cap-height 714?)

* uni0EB6 (U+0EB6): X=316.0,Y=713.0 (should be at cap-height 714?)

* uni0EB6.narrow: X=201.0,Y=713.0 (should be at cap-height 714?)

* uni0EB6.narrow: X=306.0,Y=713.0 (should be at cap-height 714?)

* uni0EB7 (U+0EB7): X=211.0,Y=713.0 (should be at cap-height 714?)

* uni0EB7 (U+0EB7): X=316.0,Y=713.0 (should be at cap-height 714?)

* uni0EB7.narrow: X=201.0,Y=713.0 (should be at cap-height 714?)

* uni0EB7.narrow: X=306.0,Y=713.0 (should be at cap-height 714?)

* uni0EC9 (U+0EC9): X=129.0,Y=712.0 (should be at cap-height 714?)

* uni0EC9 (U+0EC9): X=219.5,Y=714.5 (should be at cap-height 714?)

* uni0EC9.narrow: X=129.0,Y=712.0 (should be at cap-height 714?)

* uni0EC9.narrow: X=219.5,Y=714.5 (should be at cap-height 714?)

* uni0ECA (U+0ECA): X=344.0,Y=715.0 (should be at cap-height 714?)

* uni0ECA.narrow: X=343.5,Y=715.0 (should be at cap-height 714?)

* yamakkanlao (U+0ECE): X=352.0,Y=713.0 (should be at cap-height 714?)

* yamakkanlao (U+0ECE): X=176.0,Y=713.0 (should be at cap-height 714?)

* uni0ECE.centre: X=352.0,Y=713.0 (should be at cap-height 714?)

* uni0ECE.centre: X=176.0,Y=713.0 (should be at cap-height 714?)

* uni0ECE.narrow: X=337.0,Y=713.0 (should be at cap-height 714?)

* uni0ECE.narrow: X=171.0,Y=713.0 (should be at cap-height 714?)

* uni0ED8 (U+0ED8): X=420.5,Y=1.5 (should be at baseline 0?)

* uni0ED8 (U+0ED8): X=504.5,Y=0.5 (should be at baseline 0?)

* uni0EC6 (U+0EC6): X=124.0,Y=2.0 (should be at baseline 0?)

* C (U+0043): X=457.5,Y=0.5 (should be at baseline 0?)

* Cacute (U+0106): X=457.5,Y=0.5 (should be at baseline 0?)

* Ccaron (U+010C): X=457.5,Y=0.5 (should be at baseline 0?)

* Ccedilla (U+00C7): X=457.5,Y=0.5 (should be at baseline 0?)

* Cdotaccent (U+010A): X=457.5,Y=0.5 (should be at baseline 0?)

* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

* Oslash (U+00D8): X=454.5,Y=715.5 (should be at cap-height 714?)

* Oslash (U+00D8): X=287.0,Y=-1.0 (should be at baseline 0?)

* b (U+0062): X=66.5,Y=713.5 (should be at cap-height 714?)

* bracketleft (U+005B): X=239.0,Y=713.0 (should be at cap-height 714?)

* bracketright (U+005D): X=121.5,Y=713.0 (should be at cap-height 714?)

* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

* d (U+0064): X=370.5,Y=713.5 (should be at cap-height 714?)

* dcaron (U+010F): X=370.5,Y=713.5 (should be at cap-height 714?)

* dcroat (U+0111): X=370.5,Y=713.0 (should be at cap-height 714?)

* f (U+0066): X=331.0,Y=712.5 (should be at cap-height 714?)

* five (U+0035): X=328.0,Y=0.5 (should be at baseline 0?)

* g (U+0067): X=511.5,Y=551.5 (should be at x-height 550?)

* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

* germandbls (U+00DF): X=352.5,Y=2.0 (should be at baseline 0?)

* h (U+0068): X=66.5,Y=713.5 (should be at cap-height 714?)

* hbar (U+0127): X=66.5,Y=713.5 (should be at cap-height 714?)

* k (U+006B): X=66.5,Y=713.5 (should be at cap-height 714?)

* uni0137 (U+0137): X=66.5,Y=713.5 (should be at cap-height 714?)

* l (U+006C): X=66.5,Y=713.5 (should be at cap-height 714?)

* lacute (U+013A): X=66.5,Y=713.5 (should be at cap-height 714?)

* lcaron (U+013E): X=66.5,Y=713.5 (should be at cap-height 714?)

* uni013C (U+013C): X=66.5,Y=713.5 (should be at cap-height 714?)

* lslash (U+0142): X=81.5,Y=713.5 (should be at cap-height 714?)

* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

* ordfeminine (U+00AA): X=126.5,Y=713.0 (should be at cap-height 714?)

* paragraph (U+00B6): X=522.0,Y=713.0 (should be at cap-height 714?)

* parenleft (U+0028): X=314.0,Y=715.0 (should be at cap-height 714?)

* parenright (U+0029): X=32.0,Y=715.0 (should be at cap-height 714?)

* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

* question (U+003F): X=137.0,Y=715.5 (should be at cap-height 714?)

* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

* quotedblleft (U+201C): X=420.0,Y=715.0 (should be at cap-height 714?)

* quotedblleft (U+201C): X=220.0,Y=715.0 (should be at cap-height 714?)

* quoteleft (U+2018): X=220.0,Y=715.0 (should be at cap-height 714?)

* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

* s (U+0073): X=123.0,Y=2.0 (should be at baseline 0?)

* sacute (U+015B): X=123.0,Y=2.0 (should be at baseline 0?)

* scaron (U+0161): X=123.0,Y=2.0 (should be at baseline 0?)

* scedilla (U+015F): X=123.0,Y=2.0 (should be at baseline 0?)

* uni0219 (U+0219): X=123.0,Y=2.0 (should be at baseline 0?)

* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

* sterling (U+00A3): X=457.5,Y=1.5 (should be at baseline 0?)

* t (U+0074): X=97.0,Y=551.0 (should be at x-height 550?)

* thorn (U+00FE): X=66.5,Y=713.5 (should be at cap-height 714?)

* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



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
| 0 | 0 | 1 | 8 | 95 | 7 | 140 | 0 | 
| 0% | 0% | 0% | 3% | 38% | 3% | 56% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
