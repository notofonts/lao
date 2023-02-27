## Fontbakery report

Fontbakery version: 0.8.11b0

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansLaoLoopedUI/googlefonts/ttf', 'fonts/NotoSansLaoLoopedUI/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Sans Lao Looped UI' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent underline thickness? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/family/underline_thickness">com.google.fonts/check/family/underline_thickness</a>)</summary><div>


* 🔥 **FAIL** Thickness of the underline is not the same across this family. In order to fix this, please make sure that the underlineThickness value is the same in the 'post' table of all of this family font files.
Detected underlineThickness values are:
	fonts/NotoSansLaoLoopedUI/googlefonts/ttf/NotoSansLaoLoopedUI-Black.ttf: 130
	fonts/NotoSansLaoLoopedUI/googlefonts/ttf/NotoSansLaoLoopedUI-Bold.ttf: 107
	fonts/NotoSansLaoLoopedUI/googlefonts/ttf/NotoSansLaoLoopedUI-ExtraBold.ttf: 117
	fonts/NotoSansLaoLoopedUI/googlefonts/ttf/NotoSansLaoLoopedUI-ExtraLight.ttf: 33
	fonts/NotoSansLaoLoopedUI/googlefonts/ttf/NotoSansLaoLoopedUI-Light.ttf: 47
	fonts/NotoSansLaoLoopedUI/googlefonts/ttf/NotoSansLaoLoopedUI-Medium.ttf: 81
	fonts/NotoSansLaoLoopedUI/googlefonts/ttf/NotoSansLaoLoopedUI-Regular.ttf: 70
	fonts/NotoSansLaoLoopedUI/googlefonts/ttf/NotoSansLaoLoopedUI-SemiBold.ttf: 93
	fonts/NotoSansLaoLoopedUI/googlefonts/ttf/NotoSansLaoLoopedUI-Thin.ttf: 24
	fonts/NotoSansLaoLoopedUI/googlefonts/variable-ttf/NotoSansLaoLoopedUI[wdth,wght].ttf: 70
 [code: inconsistent-underline-thickness]
</div></details><br></div></details><details><summary><b>[13] NotoSansLaoLoopedUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- 291 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.8x (1800) [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Lao Looped UI Black [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 438, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao Looped UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- saraUlao.ngoNgu

	- saraUulao.ngoNgu

	- space.BRACKET.87

	- uni0EA5.BRACKET.110 

	- uni0EAA.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* uni0E87 (U+0E87): X=83.0,Y=-2.0 (should be at baseline 0?)

	* uni0E9B (U+0E9B): X=480.0,Y=715.0 (should be at cap-height 714?)

	* uni0E9D (U+0E9D): X=560.0,Y=715.0 (should be at cap-height 714?)

	* uni0E9F (U+0E9F): X=686.0,Y=715.0 (should be at cap-height 714?)

	* uni0EA2 (U+0EA2): X=471.0,Y=715.0 (should be at cap-height 714?)

	* uni0EC6 (U+0EC6): X=176.0,Y=-2.0 (should be at baseline 0?)

	* uni0ED8 (U+0ED8): X=199.0,Y=-1.5 (should be at baseline 0?)

	* uni0EDD (U+0EDD): X=888.0,Y=2.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=96.0,Y=713.0 (should be at cap-height 714?) 

	* 13 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E84 (U+0E84) contains a short segment L<<317.0,233.0>--<308.0,233.0>>

	* uni0E84 (U+0E84) contains a short segment B<<210.0,203.0>-<215.0,204.0>-<220.0,204.0>>

	* uni0E8A (U+0E8A) contains a short segment B<<427.0,0.0>-<427.0,11.0>-<421.5,19.0>>

	* uni0E8A (U+0E8A) contains a short segment B<<243.5,152.5>-<233.0,146.0>-<233.0,134.0>>

	* uni0E8D (U+0E8D) contains a short segment B<<220.0,339.0>-<215.0,339.0>-<210.0,340.0>>

	* uni0E8D (U+0E8D) contains a short segment L<<317.0,199.0>--<303.0,199.0>>

	* uni0E97 (U+0E97) contains a short segment B<<325.0,432.0>-<325.0,432.0>-<325.0,432.0>>

	* uni0E9A (U+0E9A) contains a short segment B<<325.0,432.0>-<325.0,431.0>-<325.0,432.0>>

	* uni0E9B (U+0E9B) contains a short segment B<<325.0,432.0>-<325.0,431.0>-<325.0,432.0>>

	* uni0E9F (U+0E9F) contains a short segment B<<325.0,432.0>-<325.0,432.0>-<325.0,432.0>> 

	* 38 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0EC8 (U+0EC8): L<<224.0,827.0>--<224.0,746.0>> -> L<<224.0,746.0>--<215.0,605.0>> 

	* uni0EC8 (U+0EC8): L<<60.0,605.0>--<50.0,746.0>> -> L<<50.0,746.0>--<50.0,827.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] NotoSansLaoLoopedUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- 291 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.8x (1800) [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Lao Looped UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 438, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- saraUlao.ngoNgu

	- saraUulao.ngoNgu

	- space.BRACKET.87

	- uni0EA5.BRACKET.110 

	- uni0EAA.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=386.0,Y=-0.5 (should be at baseline 0?)

	* uni0E82 (U+0E82): X=279.0,Y=-0.5 (should be at baseline 0?)

	* uni0E8A (U+0E8A): X=444.0,Y=-2.0 (should be at baseline 0?)

	* uni0E8A (U+0E8A): X=279.0,Y=-0.5 (should be at baseline 0?)

	* uni0EB5 (U+0EB5): X=362.5,Y=715.0 (should be at cap-height 714?)

	* uni0EB5 (U+0EB5): X=197.5,Y=715.0 (should be at cap-height 714?)

	* uni0EC3 (U+0EC3): X=288.0,Y=716.0 (should be at cap-height 714?)

	* uni0EC4 (U+0EC4): X=239.0,Y=715.0 (should be at cap-height 714?)

	* uni0EC9 (U+0EC9): X=240.0,Y=713.0 (should be at cap-height 714?)

	* uni0ECA (U+0ECA): X=50.0,Y=715.0 (should be at cap-height 714?) 

	* 15 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E81 (U+0E81) contains a short segment B<<142.0,199.0>-<142.0,199.0>-<143.0,199.0>>

	* uni0E94 (U+0E94) contains a short segment L<<222.0,199.0>--<223.0,199.0>>

	* uni0E95 (U+0E95) contains a short segment L<<222.0,199.0>--<223.0,199.0>>

	* uni0E96 (U+0E96) contains a short segment L<<266.0,199.0>--<267.0,199.0>>

	* uni0E97 (U+0E97) contains a short segment B<<307.0,435.0>-<307.0,434.0>-<307.0,433.0>>

	* uni0E99 (U+0E99) contains a short segment L<<136.0,340.0>--<135.0,340.0>>

	* uni0E9A (U+0E9A) contains a short segment B<<307.0,435.0>-<307.0,434.0>-<307.0,433.0>>

	* uni0E9C (U+0E9C) contains a short segment B<<223.0,340.0>-<223.0,340.0>-<222.0,340.0>>

	* uni0E9D (U+0E9D) contains a short segment B<<223.0,340.0>-<223.0,340.0>-<222.0,340.0>>

	* uni0E9E (U+0E9E) contains a short segment B<<307.0,435.0>-<307.0,434.0>-<307.0,433.0>> 

	* 23 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0EC8 (U+0EC8): L<<188.0,813.0>--<188.0,737.0>> -> L<<188.0,737.0>--<181.0,607.0>> 

	* uni0EC8 (U+0EC8): L<<58.0,607.0>--<50.0,737.0>> -> L<<50.0,737.0>--<50.0,813.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[14] NotoSansLaoLoopedUI-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- 291 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.8x (1800) [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Lao Looped UI ExtraBold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 438, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao Looped UI ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- saraUlao.ngoNgu

	- saraUulao.ngoNgu

	- space.BRACKET.87

	- uni0EA5.BRACKET.110 

	- uni0EAA.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=388.0,Y=-1.5 (should be at baseline 0?)

	* uni0E8A (U+0E8A): X=436.0,Y=-1.0 (should be at baseline 0?)

	* uni0E9B (U+0E9B): X=489.0,Y=713.0 (should be at cap-height 714?)

	* uni0E9D (U+0E9D): X=565.0,Y=713.0 (should be at cap-height 714?)

	* uni0E9F (U+0E9F): X=685.0,Y=713.0 (should be at cap-height 714?)

	* uni0EA2 (U+0EA2): X=480.0,Y=713.0 (should be at cap-height 714?)

	* uni0EB3 (U+0EB3): X=-285.0,Y=712.0 (should be at cap-height 714?)

	* uni0EB3 (U+0EB3): X=-27.0,Y=712.0 (should be at cap-height 714?)

	* uni0EB3 (U+0EB3): X=-108.0,Y=712.0 (should be at cap-height 714?)

	* uni0EB3 (U+0EB3): X=-204.0,Y=712.0 (should be at cap-height 714?) 

	* 23 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E84 (U+0E84) contains a short segment L<<314.0,234.0>--<299.0,234.0>>

	* uni0E84 (U+0E84) contains a short segment B<<198.0,199.0>-<207.0,201.0>-<216.0,201.0>>

	* uni0E87 (U+0E87) contains a short segment B<<213.0,443.0>-<204.0,443.0>-<196.0,443.0>>

	* uni0E8D (U+0E8D) contains a short segment B<<216.0,340.0>-<207.0,340.0>-<198.0,342.0>>

	* uni0E8D (U+0E8D) contains a short segment L<<314.0,205.0>--<295.0,205.0>>

	* uni0E97 (U+0E97) contains a short segment B<<315.0,434.0>-<315.0,433.0>-<315.0,433.0>>

	* uni0E9B (U+0E9B) contains a short segment B<<315.0,434.0>-<315.0,433.0>-<315.0,433.0>>

	* uni0E9F (U+0E9F) contains a short segment B<<315.0,434.0>-<315.0,433.0>-<315.0,433.0>>

	* uni0EA2 (U+0EA2) contains a short segment B<<216.0,340.0>-<207.0,340.0>-<198.0,342.0>>

	* uni0EA2 (U+0EA2) contains a short segment L<<314.0,205.0>--<295.0,205.0>> 

	* 18 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0EC8 (U+0EC8): L<<205.0,820.0>--<205.0,741.0>> -> L<<205.0,741.0>--<197.0,606.0>> 

	* uni0EC8 (U+0EC8): L<<59.0,606.0>--<50.0,741.0>> -> L<<50.0,741.0>--<50.0,820.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0EB9 (U+0EB9): L<<122.0,-208.0>--<122.0,-208.0>>/B<<122.0,-208.0>-<88.0,-203.0>-<69.0,-182.0>> = 8.365886124032546 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansLaoLoopedUI-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- 291 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.8x (1800) [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Lao Looped UI ExtraLight [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 438, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao Looped UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- saraUlao.ngoNgu

	- saraUulao.ngoNgu

	- space.BRACKET.87

	- uni0EA5.BRACKET.110 

	- uni0EAA.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=141.5,Y=1.5 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=1.5 (should be at baseline 0?)

	* comma (U+002C): X=72.0,Y=0.5 (should be at baseline 0?)

	* period (U+002E): X=141.5,Y=1.5 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=1.5 (should be at baseline 0?)

	* colon (U+003A): X=141.5,Y=1.5 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=1.5 (should be at baseline 0?)

	* question (U+003F): X=111.5,Y=715.0 (should be at cap-height 714?)

	* question (U+003F): X=189.0,Y=1.5 (should be at baseline 0?)

	* question (U+003F): X=137.5,Y=1.5 (should be at baseline 0?) 

	* 16 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E84 (U+0E84) contains a short segment B<<121.0,130.0>-<121.0,122.0>-<122.0,114.0>>

	* uni0E8D (U+0E8D) contains a short segment B<<122.0,417.0>-<121.0,409.0>-<121.0,400.0>>

	* uni0E97 (U+0E97) contains a short segment B<<256.0,450.0>-<256.0,449.0>-<256.0,449.0>>

	* uni0E9A (U+0E9A) contains a short segment B<<256.0,450.0>-<256.0,449.0>-<256.0,449.0>>

	* uni0E9E (U+0E9E) contains a short segment B<<256.0,450.0>-<256.0,449.0>-<256.0,449.0>>

	* uni0E9F (U+0E9F) contains a short segment B<<256.0,450.0>-<256.0,449.0>-<256.0,449.0>>

	* uni0EA2 (U+0EA2) contains a short segment B<<122.0,417.0>-<121.0,409.0>-<121.0,400.0>>

	* uni0EA7 (U+0EA7) contains a short segment B<<153.0,59.0>-<147.0,59.0>-<142.0,59.0>>

	* uni0EAB (U+0EAB) contains a short segment B<<256.0,450.0>-<256.0,449.0>-<256.0,449.0>>

	* uni0EAD (U+0EAD) contains a short segment L<<503.0,314.0>--<501.0,314.0>> 

	* 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0EC8 (U+0EC8): L<<55.0,614.0>--<50.0,715.0>> -> L<<50.0,715.0>--<50.0,786.0>> 

	* uni0EC8 (U+0EC8): L<<87.0,786.0>--<87.0,715.0>> -> L<<87.0,715.0>--<82.0,614.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0ED8 (U+0ED8): B<<450.0,-115.0>-<450.0,-112.0>-<451.0,-111.0>>/B<<451.0,-111.0>-<416.0,-142.0>-<378.0,-161.0>> = 3.468229258917096 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansLaoLoopedUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- 291 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.8x (1800) [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Lao Looped UI Light [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 438, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao Looped UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- saraUlao.ngoNgu

	- saraUulao.ngoNgu

	- space.BRACKET.87

	- uni0EA5.BRACKET.110 

	- uni0EAA.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* semicolon (U+003B): X=66.5,Y=-1.5 (should be at baseline 0?)

	* question (U+003F): X=107.5,Y=713.5 (should be at cap-height 714?)

	* uni0E82 (U+0E82): X=265.5,Y=2.0 (should be at baseline 0?)

	* uni0E8A (U+0E8A): X=265.5,Y=2.0 (should be at baseline 0?)

	* uni0EC3 (U+0EC3): X=96.5,Y=716.0 (should be at cap-height 714?)

	* uni0EC9 (U+0EC9): X=126.0,Y=713.0 (should be at cap-height 714?)

	* uni0EC9 (U+0EC9): X=126.0,Y=713.0 (should be at cap-height 714?)

	* uni0ECA (U+0ECA): X=387.0,Y=713.0 (should be at cap-height 714?)

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) 

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E97 (U+0E97) contains a short segment B<<186.0,360.0>-<176.0,359.0>-<166.0,359.0>>

	* uni0E9E (U+0E9E) contains a short segment B<<186.0,360.0>-<176.0,359.0>-<166.0,359.0>>

	* uni0E9F (U+0E9F) contains a short segment B<<186.0,360.0>-<176.0,359.0>-<166.0,359.0>>

	* uni0EAA (U+0EAA) contains a short segment B<<490.0,350.0>-<490.0,359.0>-<489.0,367.0>>

	* uni0EAB (U+0EAB) contains a short segment B<<186.0,360.0>-<176.0,359.0>-<166.0,359.0>>

	* uni0EAD (U+0EAD) contains a short segment L<<495.0,304.0>--<493.0,305.0>>

	* uni0EB7 (U+0EB7) contains a short segment L<<393.0,613.0>--<396.0,621.0>>

	* uni0EDC (U+0EDC) contains a short segment B<<186.0,360.0>-<176.0,359.0>-<166.0,359.0>>

	* uni0EDD (U+0EDD) contains a short segment B<<415.0,372.0>-<398.0,366.0>-<379.0,366.0>>

	* uni0EDD (U+0EDD) contains a short segment B<<675.0,166.0>-<694.0,166.0>-<711.0,160.0>> 

	* uni0EDD (U+0EDD) contains a short segment B<<186.0,360.0>-<176.0,359.0>-<166.0,359.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0EC8 (U+0EC8): L<<104.0,789.0>--<104.0,718.0>> -> L<<104.0,718.0>--<99.0,613.0>> 

	* uni0EC8 (U+0EC8): L<<55.0,613.0>--<50.0,718.0>> -> L<<50.0,718.0>--<50.0,789.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NotoSansLaoLoopedUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- 291 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.8x (1800) [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Lao Looped UI Medium [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 438, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao Looped UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- saraUlao.ngoNgu

	- saraUulao.ngoNgu

	- space.BRACKET.87

	- uni0EA5.BRACKET.110 

	- uni0EAA.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* slash (U+002F): X=376.0,Y=716.0 (should be at cap-height 714?)

	* slash (U+002F): X=110.0,Y=-2.0 (should be at baseline 0?)

	* slash (U+002F): X=9.0,Y=-2.0 (should be at baseline 0?)

	* slash (U+002F): X=275.0,Y=716.0 (should be at cap-height 714?)

	* uni0ECA (U+0ECA): X=50.0,Y=712.0 (should be at cap-height 714?)

	* uni0ECA (U+0ECA): X=474.5,Y=713.5 (should be at cap-height 714?)

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) 

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E81 (U+0E81) contains a short segment B<<147.0,193.0>-<157.0,193.0>-<165.0,192.0>>

	* uni0E81 (U+0E81) contains a short segment B<<165.0,342.0>-<159.0,341.0>-<152.0,341.0>>

	* uni0E95 (U+0E95) contains a short segment B<<190.0,192.0>-<199.0,193.0>-<208.0,193.0>>

	* uni0E96 (U+0E96) contains a short segment B<<242.0,192.0>-<251.0,193.0>-<261.0,193.0>>

	* uni0E96 (U+0E96) contains a short segment B<<138.0,342.0>-<132.0,341.0>-<125.0,341.0>>

	* uni0E99 (U+0E99) contains a short segment B<<157.0,342.0>-<148.0,341.0>-<139.0,341.0>>

	* uni0E9C (U+0E9C) contains a short segment B<<652.0,400.0>-<652.0,394.0>-<652.0,387.0>>

	* uni0E9C (U+0E9C) contains a short segment B<<208.0,341.0>-<199.0,341.0>-<190.0,342.0>>

	* uni0E9D (U+0E9D) contains a short segment B<<208.0,341.0>-<199.0,341.0>-<190.0,342.0>>

	* uni0EA1 (U+0EA1) contains a short segment B<<127.0,193.0>-<134.0,193.0>-<141.0,193.0>> 

	* 23 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0EC8 (U+0EC8): L<<149.0,798.0>--<149.0,727.0>> -> L<<149.0,727.0>--<143.0,609.0>> 

	* uni0EC8 (U+0EC8): L<<56.0,609.0>--<50.0,727.0>> -> L<<50.0,727.0>--<50.0,798.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NotoSansLaoLoopedUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- 291 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.8x (1800) [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Lao Looped UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 438, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao Looped UI' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- saraUlao.ngoNgu

	- saraUulao.ngoNgu

	- space.BRACKET.87

	- uni0EA5.BRACKET.110 

	- uni0EAA.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=177.5,Y=2.0 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=177.5,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=222.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=134.5,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=177.5,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=90.0,Y=2.0 (should be at baseline 0?) 

	* 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E96 (U+0E96) contains a short segment B<<146.0,344.0>-<136.0,342.0>-<126.0,342.0>>

	* uni0E97 (U+0E97) contains a short segment B<<278.0,440.0>-<278.0,439.0>-<278.0,439.0>>

	* uni0E97 (U+0E97) contains a short segment B<<278.0,439.0>-<278.0,437.0>-<278.0,437.0>>

	* uni0E9A (U+0E9A) contains a short segment B<<278.0,440.0>-<278.0,439.0>-<278.0,439.0>>

	* uni0E9A (U+0E9A) contains a short segment B<<278.0,439.0>-<278.0,438.0>-<278.0,437.0>>

	* uni0E9B (U+0E9B) contains a short segment B<<278.0,440.0>-<278.0,438.0>-<278.0,437.0>>

	* uni0E9C (U+0E9C) contains a short segment B<<638.0,399.0>-<638.0,396.0>-<638.0,392.0>>

	* uni0E9E (U+0E9E) contains a short segment B<<278.0,440.0>-<278.0,439.0>-<278.0,439.0>>

	* uni0E9E (U+0E9E) contains a short segment B<<278.0,439.0>-<278.0,437.0>-<278.0,437.0>>

	* uni0E9F (U+0E9F) contains a short segment B<<278.0,440.0>-<278.0,439.0>-<278.0,439.0>> 

	* 27 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0EC8 (U+0EC8): L<<132.0,792.0>--<132.0,723.0>> -> L<<132.0,723.0>--<127.0,610.0>> 

	* uni0EC8 (U+0EC8): L<<55.0,610.0>--<50.0,723.0>> -> L<<50.0,723.0>--<50.0,792.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NotoSansLaoLoopedUI-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- 291 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.8x (1800) [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Lao Looped UI SemiBold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 438, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao Looped UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- saraUlao.ngoNgu

	- saraUulao.ngoNgu

	- space.BRACKET.87

	- uni0EA5.BRACKET.110 

	- uni0EAA.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=382.5,Y=0.5 (should be at baseline 0?)

	* uni0E82 (U+0E82): X=279.5,Y=2.0 (should be at baseline 0?)

	* uni0E8A (U+0E8A): X=454.0,Y=-2.0 (should be at baseline 0?)

	* uni0E8A (U+0E8A): X=279.5,Y=2.0 (should be at baseline 0?)

	* uni0ECA (U+0ECA): X=50.0,Y=713.0 (should be at cap-height 714?)

	* uni0ECA (U+0ECA): X=143.0,Y=713.0 (should be at cap-height 714?)

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) 

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E81 (U+0E81) contains a short segment B<<144.0,196.0>-<150.0,196.0>-<155.0,196.0>>

	* uni0E81 (U+0E81) contains a short segment L<<155.0,341.0>--<149.0,341.0>>

	* uni0E88 (U+0E88) contains a short segment B<<205.0,151.0>-<200.0,150.0>-<195.0,150.0>>

	* uni0E94 (U+0E94) contains a short segment B<<205.0,196.0>-<210.0,196.0>-<215.0,196.0>>

	* uni0E95 (U+0E95) contains a short segment B<<205.0,196.0>-<210.0,196.0>-<215.0,196.0>>

	* uni0E96 (U+0E96) contains a short segment B<<253.0,196.0>-<258.0,196.0>-<264.0,196.0>>

	* uni0E96 (U+0E96) contains a short segment L<<129.0,341.0>--<124.0,341.0>>

	* uni0E97 (U+0E97) contains a short segment B<<296.0,437.0>-<296.0,436.0>-<296.0,434.0>>

	* uni0E99 (U+0E99) contains a short segment B<<147.0,341.0>-<142.0,341.0>-<137.0,341.0>>

	* uni0E9A (U+0E9A) contains a short segment B<<296.0,437.0>-<296.0,435.0>-<296.0,435.0>> 

	* 32 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0EC8 (U+0EC8): L<<167.0,805.0>--<167.0,732.0>> -> L<<167.0,732.0>--<160.0,608.0>> 

	* uni0EC8 (U+0EC8): L<<57.0,608.0>--<50.0,732.0>> -> L<<50.0,732.0>--<50.0,805.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[15] NotoSansLaoLoopedUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- 291 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.8x (1800) [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Lao Looped UI Thin [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 438, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao Looped UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- saraUlao.ngoNgu

	- saraUulao.ngoNgu

	- space.BRACKET.87

	- uni0EA5.BRACKET.110 

	- uni0EAA.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=132.5,Y=1.0 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=1.0 (should be at baseline 0?)

	* comma (U+002C): X=73.0,Y=1.5 (should be at baseline 0?)

	* period (U+002E): X=132.5,Y=1.0 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=132.5,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=73.0,Y=1.5 (should be at baseline 0?)

	* question (U+003F): X=180.5,Y=1.0 (should be at baseline 0?)

	* question (U+003F): X=138.0,Y=1.0 (should be at baseline 0?) 

	* 15 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E84 (U+0E84) contains a short segment B<<114.0,126.0>-<114.0,117.0>-<114.5,110.5>>

	* uni0E84 (U+0E84) contains a short segment B<<114.5,110.5>-<115.0,104.0>-<117.0,96.0>>

	* uni0E8D (U+0E8D) contains a short segment B<<117.0,433.0>-<115.0,426.0>-<114.5,419.5>>

	* uni0E8D (U+0E8D) contains a short segment B<<114.5,419.5>-<114.0,413.0>-<114.0,404.0>>

	* uni0E97 (U+0E97) contains a short segment B<<209.0,388.0>-<200.0,382.0>-<189.0,378.5>>

	* uni0E97 (U+0E97) contains a short segment B<<189.0,378.5>-<178.0,375.0>-<165.0,375.0>>

	* uni0E9E (U+0E9E) contains a short segment B<<209.0,388.0>-<200.0,382.0>-<189.0,378.5>>

	* uni0E9E (U+0E9E) contains a short segment B<<189.0,378.5>-<178.0,375.0>-<165.0,375.0>>

	* uni0E9F (U+0E9F) contains a short segment L<<398.0,520.0>--<424.0,520.0>>

	* uni0E9F (U+0E9F) contains a short segment B<<209.0,388.0>-<200.0,382.0>-<189.0,378.5>> 

	* 26 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0EC8 (U+0EC8): L<<55.0,615.0>--<50.0,713.0>> -> L<<50.0,713.0>--<50.0,785.0>> 

	* uni0EC8 (U+0EC8): L<<76.0,785.0>--<76.0,713.0>> -> L<<76.0,713.0>--<71.0,615.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0EB0 (U+0EB0): B<<224.0,347.5>-<203.0,328.0>-<171.0,328.0>>/B<<171.0,328.0>-<183.0,325.0>-<199.0,323.0>> = 14.036243467926457 

	* uni0EB0 (U+0EB0): B<<224.0,99.5>-<203.0,80.0>-<171.0,80.0>>/B<<171.0,80.0>-<183.0,77.0>-<199.0,75.0>> = 14.036243467926457 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>> 

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSansLaoLoopedUI[wdth,wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- 291 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.8x (1800) [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Lao Looped UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 438, but got 293 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao Looped UI' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- saraUlao.ngoNgu 

	- saraUulao.ngoNgu
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni034F (U+034F) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=177.5,Y=2.0 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=2.0 (should be at baseline 0?)

	* ampersand (U+0026): X=377.5,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=177.5,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=222.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=134.5,Y=2.0 (should be at baseline 0?)

	* uni0EA5 (U+0EA5): X=397.5,Y=1.5 (should be at baseline 0?) 

	* 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 54 | 82 | 1150 | 65 | 902 | 0 |
| 0% | 2% | 4% | 51% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
